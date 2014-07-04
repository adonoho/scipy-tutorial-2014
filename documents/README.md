# Agenda

[TOC]

## 8:00 am First Session

### Getting Started

* Say *Hi!* to the instructors
* Introduce yourself to the person sitting next to you, they will be your
  partner
* Make sure you successfully completed the [preparation](Preparation.md) tasks

### Introduction

Introduction (10min) - Luis

* History of scientific societies and publications
    * http://54.225.78.7/LearningEncounters/Reproducible-Research-Part-I/#/
    * Leeuwenhoek was the Man !
    * The Invisible College
    * Nullius in Verba

### Data Acquisition.

Replication of the early microscope experiments by Antonie Leeuwenhoek

* Data collection - Image Acquisition (15 min) Matt and Luis
  * [DataAcquisition.md](DataAcquisition.md)
  * Hands on: Cell camera phone microscope
  * With drop of water
  * Hands on: Each pair acquires images

### Data Sharing

Data Sharing (30min)

* [DataSharing.md](DataSharing.md)
* Image gathering, storage, and sharing (15min) - Luis
  * Figshare (www.figshare.com)
  * MIDAS (www.midasplatform.com)
  * Girder (http://girder.readthedocs.org/en/latest)
  * Hands on: Upload the images
* Hands on: Download data via RESTful API (15min)
  * Provenance and
  * Python scripts
  * Hands on: Download the data via HTTP


## 9:00 am Second Session

### Local Data Processing

Computational Environment (20min) - Aashish

* [ComputationalEnvironment.md](ComputationalEnvironment.md)
* Package versioning
* Virtual Machines
* Docker
* Cloud services
* Hands on:
  * Create a Docker image and container
  * Run our tutorial package verification script

### Revision Control

Revision Control with Git (20min) - Steve

* Keeping track of changes
* Unique hashes
* DOI
* Hands on:
  * Create a branch
  * Make a commit
  * Push the branch
  * Create a citable version: https://guides.github.com/activities/citable-code/

### IPython Notebooks and SimpleITK

Python SimpleITK scripts (20min) Matt

* [DataProcessing.md](DataProcessing.md)
* Data analysis, particle counting.
* Hands on:
  * Run scripts on new data
  * Generate histogram for the data

## 10:00 am Break (15min)

## 10:15 am Third Session

### Testing

Testing (30min)  Jc

* Unit testing with known data
* Regression testing with known data
* Hands on:
  * Run tests
  * Add coverage for another method to the unit tests

### Modern Scientific Publishing

Literate Programming - Dexy (30min) Ana

* Article generation
* RST to HTML, etc
* GitHub replication and sharing
* Hands on:
  *  Run dexy to generate a PDF document


## 11:15 am Fourth Session

### Insight Journal

Submitting an article to a Reproducible Journal (20 min)

* Submit Article to the Insight Journal
* Point to github fork, for source code

### Replicate or Perish !

Attempt to replicate articles (40 min)

* Group assignment
* Replication attempt
* Sharing observations
