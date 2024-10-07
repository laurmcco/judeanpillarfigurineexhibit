---
title: Relight Artifacts
layout: essay
permalink: /rti.html
custom-foot: js/relight-page-js.html
---

Welcome to the Reflectance Transformation Imaging Laboratory. Here you will find instructions for viewing, manipulating, and scrutinizing RTIs of Judean Pillar Figurine fragments.

Click anywhere on the RTI images to change the direction of a virtual light. Zoom in to observe the figurine's surface and anything of interest upon it (for example tool marks, fingerprints, paint). Click the "layers" icon to explore various rendering environments: “normals” shows the surface shape through false color, “diffuse” shows surface shape with color removed, and “specular” shows the surface with a shiny quality. In "specular" mode, you can manipulate the direction of light at the same time that you increase or decrease the light’s intensity via a slider.

1) Browse the first RTI image below. This artifact (labelled B2018.1.1, held at the Badè Museum) is special for the amount of paint it still contains. What colors do you see, and where? What surface characteristics do you observe?

2) Use the layers icon to enter the “normals” mode and the “specular” mode. There is one area that has a circular mark on the surface. Can you find it? Once you do, or if you can't find it after a few minutes, click the buttons below.

{% include feature/relight-page-viewer.html objectid="bad_0004" %}

{% capture pupil %}
The pupil. For some reason, there is a rim around the pupil. Switch into the default/"light" mode. What color paint fills the pupil area? You have just discovered that RTI can show color not only chromatically but through marks left on the surface, invisible to the naked eye. There is a similar circular mark in the pupil of the other eye, though more faint. Now that you have some experience manipulating a virtual light and observing this artifact's surface topography, can you find the circular mark in the other eye?  Note: the right eye contains a small circular "inclusion" (like a pebble) that fell away from the surface after the figurine was fired. The circular mark you are looking for is larger, about the same size as the one in the left eye.
{% endcapture %}
{% include feature/collapse.html button="Where is the circular mark on this figurine's surface?" color="outline-info" title="Answer" text=pupil %}

{% capture circular %}
Whatever process was used to create this figurine’s pupils, it involved a circular rim on the surface of both eyes. Particularly in the first RTI–the one of the left eye–it seems that the artisan pre-impressed the pupils with a circular tool (or even a fingertip) prior to painting the area black. The normals view shows surface texture through encoded colors, where green represents a dip in surface topography and blue represents a rise. The left eye shows a bulge in the clay (northwest portion of the pupil), as if the tool pushed wet clay underneath and created the circular rim we are investigating now.

We cannot be sure what caused the pupil marks. But RTI expands the conversations we can have about Judean Pillar Figurines, here by giving evidence for special manufacture of the eyes. Fine surface details reveal that the eyes were crafted differently than the rest of this figurine. For example, black paint was also used for eyeliner and neck bands, without corresponding marks. Investigate the eyeliner and neck bands for yourself. The artisan used an alternate method to paint the pupils than the rest of the figurine, which makes them seem important. Usually interpreters stress the breasts as the most crucial part of the Judean Pillar Figurine, but now we have reason to appreciate the eyes, too.
{% endcapture %}
{% include feature/collapse.html button="What could have caused the circular mark on this figurine’s surface?" color="outline-primary" title="Answer" text=circular %}

View the remaining RTI images of this and other artifacts to find new points of intrigue on the Judean Pillar Figurine. I have guided you through an analysis of B2018.1.1's black pupils, which involves comparison with its black eyeliner and black neck bands. Alternatively, one might investigate this figurine fragment's clay composition and temper (loss of straw particles seems evident in the right eye and on the right side of the headband) or process of clay preparation (the rocky inclusion in the right eye suggests expedient clay sifting, underscoring the likelihood that JPFs were not "luxury" objects).
   
{% include feature/relight-page-viewer.html objectid="bad_0003" %}

{% include feature/relight-page-viewer.html objectid="bad_0005" %}

## Give Pause

Do you find that the images carry an air of authority? Do they make you hesitant to question my findings? Like all interpretations, mine must be held up to scrutiny. 

I use RTI views of B2018.1.1 to argue that Judean Pillar Figurine artisans spent extra time and effort crafting the eyes. However, one needs to be able to read a "normals" image to test that hypothesis, and even then, the data are not incontrovertible. The northwest area of the left pupil has a bulge, but there is surface encrustation in most other places along this pupil's rim. The encrustation obfuscates our view of the evidence required to confirm my interpretation. Encrustation also exists around the pupil rim of the right eye. RTI provides detailed views of B2018.1.1's surface, contributing new data points that invite fresh questions. We should not accept the resulting interpretations without "reading" the RTI images for ourselves, which also involves checking that the images were collected using "best practice" standards that ensure each RTI image is reproducible <https://culturalheritageimaging.org/What_We_Offer/Downloads/DLN/index.html>.

## Uses of RTI

- Object documentation, for example to track deterioration over time

- Non-invasive object analysis, for example by providing a window into manufacture without causing any destruction to the object. Manufacture clues reveal artisan intentionality, which presumably reflects artisan values and/or the values of the audiences that created demand for the Judean Pillar Figurines to be made. Manufacture clues can also help modern audiences pursue questions of artisan guilds and trade, for example by tracing distinctive workshops techniques. How many other figurines from Mizpah contain pupil impressions? How many from other sites?

- Digitization that works toward democratizing access to restricted objects, for example those held by museums. This also curbs (but never replaces) the need for an object to be studied in-person

- Can be combined with other methods, like microscopy

- Note: a current drawback of RTI compared to other methods of computational photography like 3D modeling is that RTI does not permit measurement. Also, not all materials respond well to RTI analysis. Shiny objects interfere with the method of RTI capture and are difficult to image.

## Browse All RTIs

{% assign rtis = site.data.web-exhibit | where: 'display_template', 'rti_viewer' %}
<div class="row">{% for r in rtis %}
<div class="col-6 col-md-4">{% include feature/relight-page-viewer.html objectid=r.objectid %}</div>{% endfor %}
</div>

## Go Further

To learn more about RTI, visit:

- [Cultural Heritage Imaging RTI](https://culturalheritageimaging.org/Technologies/RTI/)

- [AIC Wiki RTI](https://www.conservation-wiki.com/wiki/Reflectance_Transformation_Imaging_(RTI))

- [Cultural Heritage Imaging publications](https://culturalheritageimaging.org/What_We_Do/Publications/)

- [Tom Malzbender on Google Scholar (developer of RTI)](https://scholar.google.com/citations?user=dQNRt2MAAAAJ&hl=en)
