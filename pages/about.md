t---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="1986.001" %}

{% include feature/nav-menu.html sections="About the Virtual Digital Gallery;The Collection & Digitization;Metadata Development;Project Staff & Acknowledgments;Copyright Restrictions;About CollectionBuilder-GH" %}

## About The Virtual Digital Gallery

The Virtual Discovery Digital Gallery is a prototype digital library developed to evaluate the use of CollectionBuilder-GH as a potential platform for showcasing digitized collections at Appalachian Regional Technical School (ARTS). This virtual gallery provides access to digitized artwork for use by art historians, researchers, students, and the general public. Each of these users has unique search behaviors and accessibility needs, and understanding these diverse user groups is important to ensuring that the digital gallery supports effective discovery, interpretation, and engagement with the collection.


## The Collection & Digitization

While the Virtual Discovery Digital Gallery may expand in the future, project staff have partnered with the Taubman Museum of Art in Roanoake, Virginia and Virginia Tech (VT) to provide an initial collection of digitized artwork sufficient to test the capabilities of CollectionBuilder-GH. 

The Taubman Museum of Art has partnered with Virginia Tech to digitize their collection, with the joint goals of digital preservation and online access. A team from VT identified as the most feasible starting point the Taubman’s permanent collection, containing over 2,400 works of American, Southeast American Contemporary, Folk, Regional and Visionary art. Items and their accompanying museum labels have been photographed on location in gallery lighting and preserved in both TIFF format for digital preservation and as JPEG files for ease of use and access.

The collection of digital images found here is a small portion of the permanent collection held by the Taubman and covers a variety of artistic movements, techniques, and media, including oil paintings, block prints, sculpture, sketches, and correspondence. The accompanying description of each image is drawn from the museum labels and the metadata provided by the Taubman Museum of Art for the items in their permanent collection, with supplementation from the Virtual Discovery Digital Gallery staff.

## Metadata Development

Development of an appropriate metadata application profile was a significant challenge for this project due to the need to balance accurate resource description, platform requirements, and potential data harvesting and reuse. Pairing image files to existing metadata also proved difficult.

### Functional Requirements

Expected functional requirements for the expected user groups include:
- Distinguish between objects by using unique identifiers
- The ability to search or browse by title
- The ability to search or browse by creator
- The ability to search or browse by type of artwork
- The ability to search or browse by medium used in the artwork
- The ability to search or browse by subject
- The ability to browse by date or date range
- Provide context for the original artwork through description of medium, techniquest, artistic movements, or background information about the work or artist.

### Metadata Application Profile

The Virtual Discovery Gallery has developed a metadata application profile based primarily on the CDWA Lite Schema provided by the J. Paul Getty Trust. Elements were selected based on the content of the virtual collection and the requirements of the Collection Builder GH digital library platform. Some elements feature local qualifications to better fit the needs of the collection.

Each element is mapped to Dublin Core for better metadata sharing and reuse. Details of the content guidelines, application notes, and examples of each element are available in the PDF file below.


{% include feature/pdf.html objectid="VT_map" width="75" caption="Virtual Discovery Gallery Metadata Application Profile" %}

### Additional Resources

Additional resources for metadata standards and vocabularies may be found at the following links:

- CDWA Lite, [https://www.getty.edu/research/publications/electronic_publications/cdwa/cdwalite.pdf](https://www.getty.edu/research/publications/electronic_publications/cdwa/cdwalite.pdf)
- Dublin Core Metadata Terms, [https://www.dublincore.org/specifications/dublin-core/dcmi-terms/](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/)
- Getty Vocabularies, [https://www.getty.edu/research/tools/vocabularies/](https://www.getty.edu/research/tools/vocabularies/)
- Library of Congress Authorities, [https://authorities.loc.gov/](https://authorities.loc.gov/)


## Project Staff & Acknowledgments

This project has been the work of:
- Eric Brown
- David Tate
- Krystal White

Much thanks to the Taubman Museum of Art for providing access to their permanent collection, and to the staff at Virginia Tech for photographing the artwork and making the image files and metadata available for this project.


## Copyright Restrictions

All images are subject to copyright, as indicated in the individual item records. All text featured here and the metadata application profile provided have been developed by the project staff and are subject to a Creative Commons CC BY-NC 4.0 license. Reusers may distribute, remix, adapt, and build upon the material in any medium or format for noncommercial purposes only, and only so long as attribution is given to the creator.

## About CollectionBuilder-GH

This site is generated using [CollectionBuilder-GH](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPG images or PDF documents

The template repository features four objects from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital). 

For full details of creating your own collection site, visit [CollectionBuilder Documentation](https://collectionbuilder.github.io/cb-docs/)!

