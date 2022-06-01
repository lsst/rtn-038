:tocdepth: 1

.. sectnum::

.. Metadata such as the title, authors, and description are set in metadata.yaml

.. TODO: Delete the note below before merging new content to the main branch.

.. note::

   **This technote is a work-in-progress.**


Introduction
============

The document provides the detailed mathematical definitions for all normative LSST science performance metrics 

The LSST Science Requirements Document defines a set of normative science performance metrics for the LSST, driven by the four science themes - studying the nature of dark matter and dark energy, exploring the dynamic and transient sky, mapping the Milky Way, and taking an inventory of the Solar System (add citation to overview paper).
In this document, we present the detailed algorithms for all the normative science performance metrics defined in the SRD, LSR, OSS and DMSR.
Many requirements will have more than one requirement identifier.
This reflects the fact that many high-level requirements are flowed down to the ultimate subsystem that is responsible for implementing the metric. 
For convienience, we have provided links to all the requirements that describe the same metric. 

The document is organized into sections corresponding to the different types of metrics, with each section containng the definitions for all metics of that type. 
To add a new metric definition, copy and paste the template "<type> Metric X ". 


Image quality Metrics
=====================

This section gives the mathematical definitions for all defined image quality metrics. 


Ellipticity correlation
-----------------------
Name: TE12

Specification:  The averaged E1, E2, and Ex residual PSF ellipticity correlations

Requirement Identifier(s): LPM-17, LSR, OSS, DMSR (DMS-REQ-0360)

unit: none

Detailed Algorithm:


Photometry Performance Metrics
==============================

This section gives the mathematical definitions for all defined photometry performance metrics. 


Photometric Repeatabililty
--------------------------
Name: PA1 

Specification: The maximum rms of the unresolved source magnitude distribution around the median value.

Requirement Identifier(s): LPM-17, LSR, OSS, DMSR (DMS-REQ-0359)

unit: mmag

Detailed Algorithm:


Astrometry Performance Metrics
==============================

This section gives the mathematical definitions for all defined astrometry performance metrics 


Astrometric ...
--------------------------
Name: AFX

Specification: The maximum fraction of astrometric distances that deviate by more than AD1 milliarcsec

Requirement Identifier(s): LPM-17, LSR, OSS, DMSR (DMS-REQ-0360)

unit: percent

Detailed Algorithm:




<template> Metrics
==================

This section gives the mathematical definitions for all <science type> performance metrics 


<tempalate> Metric X1
---------------------
Name:

Specification:

Requirement Identifier(s) (with links):

Detailed Algorithm:



.. Make in-text citations with: :cite:`bibkey`.
.. Uncomment to use citations
 .. rubric:: References
 
 .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
    :style: lsst_aa

