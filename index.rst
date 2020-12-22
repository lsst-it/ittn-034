..
  Technote content.

  See https://developer.lsst.io/restructuredtext/style.html
  for a guide to reStructuredText writing.

  Do not put the title, authors or other metadata in this document;
  those are automatically added.

  Use the following syntax for sections:

  Sections
  ========

  and

  Subsections
  -----------

  and

  Subsubsections
  ^^^^^^^^^^^^^^

  To add images, add the image file (png, svg or jpeg preferred) to the
  _static/ directory. The reST syntax for adding the image is

  .. figure:: /_static/filename.ext
     :name: fig-label

     Caption text.

   Run: ``make html`` and ``open _build/html/index.html`` to preview your work.
   See the README at https://github.com/lsst-sqre/lsst-technote-bootstrap or
   this repo's README for more info.

   Feel free to delete this instructional comment.

:tocdepth: 1

.. Please do not modify tocdepth; will be fixed when a new Sphinx theme is shipped.

.. sectnum::

.. TODO: Delete the note below before merging new content to the master branch.

.. note::

   **This technote is not yet published.**

   Summit base link

.. Add content here.

Introduction
============

The following documentation will describe the current deployment of the fiber optic connections. These connections start at the AURA datacenter located in the City of La Serena, 
Coquimbo, and extend towards the communications room located in Cerro Pachon and Cerro Tololo in the interior valleys of Vicuña, Coquimbo.  

This document will also provide insight into the fiber optic connections, its areas where these are deployed, and the routes that these follow. Along with the procedures 
followed in case of failures and repairs. 

The idea to connect the various projects that Aura is responsible for including Tololo, Rubin, SOAR, Gemini, and any other project that might require a physical connection arose 
from the idea of using an existing fiber optic cable that extends along route D41 from Santiago to La Serena. This cable was installed by three major telecommunication companies 
in Chile (Movistar, Claro, and Entel). This cable also serves as a backup for the national fiber optic cable that runs from Arica to Punta Arenas on Panamericana Highway Ruta 5.

Aura used this opportunity to connect their various projects to this cable and extend their communication towards the Aura data center located in La Serena and the US.  

It is worth mentioning, when this document refers to the term Aura BDC it refers to the data center that is in the City of La Serena. When the document alludes to the Aura site 
itself, it refers to the land that is owned by Aura from the control gate into the various project sites. 

Note: OS2 Single-Mode fiber was used to connect the following sites: Cerro Pachon, Tololo, La Serena Base Data Center (BDC), Movistar Data Center, and route D41. 

Fiber optic route from BDC to Data center Movistar
==================================================

The current deployment of the fiber optic connections starts at the La Serena Base Data Center (BDC) in rack A1 which are spliced in an optical terminal in slot U48 and U47 of 
this rack. These connections pass through the interior of the Aura BDC and are spliced to the Movistar trunk that is located in the exterior of the Aura BDC. This cable extends 
towards Movistar Data center main plant and is connected to one of their optical terminals, Movistar has given these cables the name of CAP01 and CAP02. These cables provide 
Aura BDC many services, first, they provide connectivity to the various Aura projects located in the interior of Vicuña. Second, they also provide internet connectivity to the 
Aura building and base data center systems.

It is important to mention that these cables do not provide Aura with a main and backup service in case of failure, this is why each cable contains independent services that are 
different from one another.  

Cap 01- Cap 02 image
--------------------
.. figure:: /_static/cap.png
   :name: cap
   :width: 700 px

Note: The image displayed above, illustrated approximately how the cable is routed through the various points of interest. 

Movistar Data Center Main Plant to Vicuña
=========================================

At Movistar main plant a 96 Strand single-mode cable is born this cable is routed along route D41 road to Vicuña Aura project site, here 4 fibers are separated from this 96 
strand fiber optic cable enclosure for Aura and are numbered as followed (25-26-27-28) providing connectivity between the Aura BDC and its various projects located in the 
interior of the valley.

The company in charge of the stretch between Movistar Datacenter and Vicuña is the service provider Claro. Claro routed the 96 strand fiber optic enclosure to  Vicuña separating 
the fibers with 3 optic splice enclosures along route D41 whose owners are (Movistar, Claro, and Entel).

Imagen D43
----------
.. figure:: /_static/D43.png
   :name: D43
   :width: 700 px

From this point on, a 24 strand OS2 fiber optic cable is separated from Movistar splice enclosure located in route D41 and is routed using posts to the control gate located 
inside the Aura Project site. Here the cable is routed along the main road from the control gate towards San Carlos road and extends through the valley under difficult terrain 
conditions. This road is most commonly known as the service road. This cable was installed by Movistar using a series of electric and wooden poles with their respective splice 
enclosures along the way splitting off to an optical terminal located in Cerro Pachon and Cerro Tololo. 

Valle Aura Project Site Image1
-------------------------------
.. figure:: /_static/rutavalle.png
   :name: rutavalle
   :width: 700 px
   
Valle Aura Project Site Image2
------------------------------

.. figure:: /_static/ruta.PNG
   :name: ruta
   :width: 700 px
   
https://confluence.lsstcorp.org/display/IT/Technical+Documentation.+Guido   
   

San Carlos Road / Service Road
==============================

Along the service road, there are 2 important splice enclosures, one of this enclosure is commonly known in spanish as "Mufa Bifurcacion" which is in charge of distributing the 
optical fibers to Pachon and Tololo. 

Mufa Bifurcacion image
----------------------
.. figure:: /_static/mufabifu.PNG
   :name: mufabifu
   :width: 800 px


The other splice enclosure is located in Cerro Pachon inside the communication room known in Spanish as "Mufa Caseta Pachon". This splice enclosure is in charge of distributing 
the optical fibers to Pachon Hill DWDM which in turn provides connectivity to Gemini, SOAR, Tololo, Rubin Observatory, and at the same time it also routes the fibers over to 
Rubin Observatory DWDM for science use.

Mufa de Caseta Pachon image
---------------------------
.. figure:: /_static/mufacase.PNG
   :name: mufacase
   :width: 800 px

Optical Terminal
=================

It is important to mention that the rest of the optical splice enclosures that were installed in the Aura Project Site are spliced in a 1 to 1 or straight method and are all the 
same. 

In the confluence page found below, there's additional information about the optical terminals used along with their specifications and areas to which these connect. 

Optical Terminal image
-----------------------
.. figure:: /_static/optical-terminal.PNG
   :name: optical-terminal
   :width: 900 px

https://confluence.lsstcorp.org/display/IT/Fiber+Optic+-+AURA+Caseta+Pachon

Responsibilities
=================

There are four things we have to keep in mind in case of failure:

1.) Aura operations is responsible for the segment located between the control gate and the areas where the different projects reside (Cerro Pachon and Cerro Tololo). 

.. figure:: /_static/respon-aura.png
   :name: respon-aura
   :width: 700 px

2.) REUNA alongside Movistar is responsible for the segment between the control gate and route D41 where the fiber enclosure is located.

.. figure:: /_static/respon-mov.png
   :name: respon-mov
   :width: 700 px
   
3.) The segment between Movistar Datacenter in La Serena and the optical fiber enclosure mentioned in point 2 located in route D41 both REUNA, Movistar, and Claro are 
responsible for failures and repairs.

.. figure:: /_static/respon-claro.png
   :name: respon-claro
   :width: 700 px
   
4.) As for the segment between Movistar Datacenter and Aura BDC the responsibility is shared between REUNA, Movistar, and AURA Operations.

.. figure:: /_static/respon-mov-aura.png
   :name: respon-mov-aura
   :width: 700 px
   
Acronyms
========

.. include:: tabla34.rst

.. Do not include the document title (it's automatically added from metadata.yaml).

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
