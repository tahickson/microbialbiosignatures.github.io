---
layout: default
title: "The Microbial Biosignatures Project: Help"
---

<h1>Help using the database</h1>

<h2>The Hierarchy of Microbialite Traits</h2>

<p>
  The
  <a
    href="https://www.dmp.wa.gov.au/Geological-Survey/Handbook-for-the-study-and-26950.aspx"
  >
    Handbook for the Study of Microbialites (Awramik and Grey, 2020)
  </a>  (referred to as "The Handbook" throughout this site)
  uses a hierarchical structure to describe microbialites in the rock record. This structure may not be familiar to many microbialite sedimentologists and we strongly encourage you to download The Handbook and use it as a reference. Our database avoids the use of Linnaean names, but it is possible to enter these into textboxes for cross-reference purposes. 
  The basic, hierarchical structure emphasizes the multiscale nature of microbialite sedimentary
  structures and allows for a detailed, non-genetic description that encompasses
  all scales of observation.
</p>
<p>The image below illustrates this hierarchy. <i>The first</i> image shows an outcrop photo, unlabeled, of a limestone bed with microbial sedimentary structures. Most sedimentologists would recognize the domal bioherm in the lower half of the bed and the overlapping laminated limestones. <i>The second</i> image highlights the <i>megastructures</i> in this outcrop. There are two: the bioherm, an isolated buildup that formed some time before the overlapping, second megastructure, the laminated limestones that are found within a biostrome.
</p>
<p>In the third image, the megastructures are further subdivided into <i>macrostrucutures</i>, portions of the megastructure that have similar internal lithological and textural components. These macrostructures typically are of scales of decimeters. This example also illustrates another aspect of this hierarchy: some levels of the hierarchy might be coincident. The macrostructures in this case are equivalent to <i>mesostructures</i>, hand-sample scale portions of a macrostructure that have the same internal structures or textures. Mesostructures are, in our view, the outcrop-scale "building block" of microbialtes and typically form the basis for field sample collection. 
</p>
<p>Finally, in the <i>fourth</i> image we see <i>microstructures</i>, textures that can only be discerned at the microscopic scale, either in thin section or SEM analyses.
</p>
<img
  src="{{ '/images/MegaMacroMesoMicro.png' | relative_url }}"
  alt="The multiple scales of microbialite observations, from megastructure to macrostructure to mesostructure to microstructure"
  style="width: 100%; height: auto;"
/>
<p></p>
<p>These hierarchical levels form the basic structure for our database schema:
</p>
<ol>
<li><b>Project or Citation Data:</b> Descriptive metadata on the source of the data, such as age, general location, location name, citation(s), storage locale, etc.</li>
<li><b>Megastructure Data:</b> Descriptive traits of megastructures, latitude, longitude (WGS84), and other aspects that describe the microbialite over large (>1m) sizes as outlined in The Handbook.</li>
<li><b>Macrostructure Data:</b> Descriptive traits of macrostructures as outlined in The Handbook</li>
<li><b>Mesostructure Data:</b> Descriptive traits of mesostructures as outlined in The Handbook</li>
<li><b>Microstructure Data:</b> Descriptive traits of microstructures as outlined in The Handbook/li>
</ol>
</p>
