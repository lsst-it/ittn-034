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

The purpose of this document is to describe the deployment of fiber optics from the data center located in the city of La Serena in the Coquimbo region in the Aura area that 
ends in the communications rooms located at the Cerro Pachón site and Cerro Tololo in the Coquimbo region in the city of Vicuña.

The intention of this document is to detail the information of the optical fiber, its locations, and its route. It also details responsibilities for fiber optic maintenance and 
repair depending on its location.

The project to connect the telescopes arose from the existence of a new fiber optic cable that was installed by the 3 major communications companies in Chile, Movistar, Claro, 
and Entel, which runs from Santiago through towns and inland roads near the pre mountain range. that ends in the City of La Serena. To serve as a backup for the national fiber 
that is installed from Arica to Punta Arenas by highway Ruta 5 (Panamericana Highway).

With the existence of this fiber optic cable, the Aura observatories had the opportunity to connect with fiber optics from Cerro Pachón and Cerro Tololo with the city of La 
Serena and from there to the United States.

“It is worth mentioning that when this document refers to the term Aura Enclosure it refers to the land that is in the City of La Serena and when mentioning Site of Aura it 
refers to the land that is owned by Aura from the control gate and the hills Pachon and Tololo ”.

Fiber optic route from BDC to Pachon-Tololo
===========================================

The fiber optic cable laying begins from the BDC in rack A1 which are spliced at an optical terminal at locations U48 and U47 and passes through the interior of the Aura 
enclosure and is spliced to a Movistar trunk located in The exterior of the enclosure and it goes through different routes and reaches a main plant of the Movistar company and 
inside it, they connect to an internal optical terminal of the company and the name given by Movistar to these cables are CAP01 and CAP02. These cables (Cap01-02) provide us 
with many services such as telephony and Internet and also connect the Aura enclosure with the Pachón and Tololo hills. Also, be clear that these 2 cables do not provide us with 
a main and backup service, therefore each cable contains different services that are different from each other.

A 96-strand cable is born from the main plant of Movistar and is connected to the optical terminal that receives the optical fibers from the AURA campus and this cable runs 
along the D41 road to Vicuña and then reaches Santiago and the numbers of the reserved optical fibers for the AURA project that travel on the cable corresponds to the numbering 
25-26-27-28.

The service provider in charge of 96-filament fiber optics in the sector between the MOVISTAR plant and Vicuña is the company CLARO. And every certain kilometer of the route 
they installed 3 splice closures for the communications companies involved to remember are (MOVISTAR, CLARO, ENTEL).

As explained, at this point the project to connect the hills by means of a fiber optic cable arises from a junction closure that is approximately 1.5 kilometers past the 
entrance road to the site through route D41 that reaches the gate control. The company that carried out the laying works was  Movistar. The installation begins from the junction 
closure on route D41 and is extended by means of posts and enters the Aura site, passing through the gate control and passing through the main road and then enters the road 
called San Carlos, which runs through the hills through an internal road difficult to travel and this is called the site service road. The fiber optic was installed on electric 
poles and wooden poles were also installed by the Movistar company that is now owned by Aura. Along the way, splice closures were installed and the fiber optic ends in optical 
terminals on Cerro Pachon and Cerro Tololo.

Already mentioned this, we must understand that if we have any failure in the fiber optic laying in the gate control section at the site (on the hill) and up to the Movistar 
plant in the center of La Serena our regular channel is to notify Reuna and this will deliver the request to Movistar and finally it will deliver the request to the Claro 
company. Now if the problem is from the Movistar plant to the Aura enclosure and the data center, the regular conduit is Reuna, this delivers the request to Movistar and the 
latter gives us a solution. Now if we have a fault from the gate control to the connections of the Summit owned by Aura, it is clearly the responsibility of Aura Operations to 
find a solution.

.. Do not include the document title (it's automatically added from metadata.yaml).

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
