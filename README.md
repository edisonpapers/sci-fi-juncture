<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Edison Sci-Fi Exhibit"
       author="The Edison Papers Project"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->
<param ve-entity eid="Q8743"> <!-- Thomas Alva Edison -->

# Introduction

In the exhibit that follows we explore the ways in which Edison, during his lifetime, speculated about the technological future and inspired others to imagine how science and technology would change society.  The centerpiece of this exhibit is the collaboration between Edison and journalist George Parsons Lathrop on a novel of the future in the style of Edward Bellamy’s Looking Backward.  It also examines serious and satirical fiction  in which Edison appears as a protaganist and dime novels known as Edisonades.  It concludes by looking at Edison’s own speculations about the future that appeared in newspaper and journal interviews.



<param ve-image ="https://edison.rutgers.edu/images/sci-fi/scifi-lookingbackward02.jpeg">

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
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands. Were the Dutch <span ve-entity title="Black Lives Matter Movement" eid="Q19600530">human rights activists</span>? How about Thomas Alva Edison? <span ve-entity title="Thomas A. Edison" eid="Q8743" > or TA Edison?</span>
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.

<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
