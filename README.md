
 
Pull requests
Issues
Marketplace
Explore
 
@gcolati1 
JSTOR-Labs
/
juncture
Public template
 Watch 
2
 Star 13
 Fork
19
Code
Issues
11
Pull requests
2
Discussions
Actions
Projects
Wiki
Security
Insights
Sample Visual Essay
Ron Snyder edited this page on Jul 14 · 4 revisions
<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Girl with a Pearl Earring"
       author="JSTOR Labs team"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Girl with a Pearl Earring_ (Dutch: Meisje met de parel) is an oil painting by Dutch Golden Age painter Johannes Vermeer, 
dated c. 1665. Going by various names over the centuries, it became known by its present title towards the end of the 
20th century after the earring worn by the girl portrayed there.[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
Juncture, brought to you by the JSTOR Labs team
 Pages 43
Juncture User Guide

Juncture Overview

Quick Start Guides

Create a Visual Essay
Create a Juncture site
Viewing and Sharing Visual Essays
Information for Content Creators

Anatomy of a Visual Essay
Markdown Primer
Visual Essay Tags
Information for Site Owners/Administrators

Creating a new Juncture site
Customizing a Juncture site
Assigning a Custom Domain
Software Updates
Information for Developers

Setting up a development environment
Creating new components
Technical Details

Juncture Technical Architecture
How Juncture Uses Github
International Image Interoperability Framework (IIIF)
Linked Open Data (LOD)
Tips and Tricks

Creating GeoJSON Map Overlays
Creating Georeferenced Image Overlays
Finding and Using Images
Thumbnails and Banner Images
Resources and Links

Github Tutorials and Reference Documentation
Wikidata, Overviews, Tutorials and Reference Documentation
Clone this wiki locally

	
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
