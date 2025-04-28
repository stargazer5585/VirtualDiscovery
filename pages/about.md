---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="1986.001" %}

{% include feature/nav-menu.html sections="About the Virtual Digital Gallery;The Collection;Metadata;Project Staff;Copyright;About This Site" %}

## About The Virtual Digital Gallery

The Virtual Discovery Digital Gallery is a project developed as part of coursework for the University of Tennessee Knoxville School of Information Sciences. This virtual gallery provides access to digitized artwork for use by art historians, researchers, students, and the general public. Each of these users has unique search behaviors and accessibility needs, and understanding these diverse user groups ensures that the digital gallery supports effective discovery, interpretation, and engagement with the collection. 

Expected functional requirements for these varied user groups include:
- Distinguish between objects by using unique identifiers
- The ability to search by title
- The ability to search by artist
- The ability to browse by type of artwork
- The ability to search or browse by medium of the artwork
- The ability to search or browse by subject
- The ability to browse by date or date range
- Provide context for the original artwork through description of medium, techniquest, artistic movements, or background information about the work or artist.

## The Collection

While the Virtual Discovery Digital Gallery may expand in the future, the current collection consists of works from the permanent collection of the Taubman Museum of Art in Roanoke, Virginia. The Taubman Museum of Art has partnered with Virginia Tech (VT) to digitize their collection, with the goal of digital preservation and online access.  A team from VT identified the Taubman’s permanent collection as the most feasible starting point for digitization, which contains over 2,400 works of American, Southeast American Contemporary, Folk, Regional and Visionary art. Items and their accompanying museum labels have been photographed on location in gallery lighting and preserved in both TIFF format for digital preservation and as JPEG files for easier access. 

The collection of digital surrogates found here is a small portion of the permanent collection held by the Taubman and covers a variety of artistic movements, techniques, and media, including oil paintings, block prints, sculpture, sketches, and correspondence. The accompanying information about each image is drawn from metadata provided by the Taubman Museum of Art for the items in their permanent collection.

## Metadata

Development of an appropriate metadata application profile was a significant challenges of this project due to the need to balance accurate resource description, platform requirements, and potential data harvesting and reuse. 

The Virtual Discovery Gallery has developed a metadata application profile based primarily on the CDWA Lite Schema provided by the J. Paul Getty Trust. Elements were selected based on the content of the virtual collection and the requirements of the Collection Builder GH digital library platform. 

Each element is mapped to Dublin Core for better metadata sharing and reuse. Details of the content guidelines, application notes, and examples of each element are available in the PDF file below. 


{% include feature/pdf.html objectid="VT_map" width="75" caption="Virtual Discovery Gallery Metadata Application Profile" %}

## Project Staff

This project has been the work of:
- Eric Brown
- David Tate
- Krystal White

## Copyright 

All images are subject to copyright, as indicated in each item record. 
All metadata and and text featured here has been developed by the project staff and is subject to a Creative Commons CC BY-NC 4.0 license - reusers may distribute, remix, adapt, and build upon the material in any medium or format for noncommercial purposes only, and only so long as attribution is given to the creator. 

## About This Site

This site is generated using [CollectionBuilder-GH](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPG images or PDF documents

The template repository features four objects from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital). 

For full details of creating your own collection site, visit [CollectionBuilder Documentation](https://collectionbuilder.github.io/cb-docs/)!

