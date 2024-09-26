---

permlaink: /
layout: single
classes: wide
title: "About"
author_profile: true
header:
  image: /assets/san_pedro.JPG

---
<script src="https://kit.fontawesome.com/ebdc698a08.js" crossorigin="anonymous"></script>

I am a postdoctoral researcher at the NORSAR research facility in Kjeller, Norway. In
investigate subsurface fluid processes fault zones and subduction zones using
seismology. My current research revolves around developing a method to determine moment
tensors of small earthquakes. Previously, I worked on detecting and locating
earthquakes, computing earthquake magnitudes, determining fault plane solutions and
moment tensors, receiver function processing, calculation of seismic tomographies and
software development to learn about earthquakes and Earth's interior structure.

## Research Portfolio

### Structural imaging and modeling

![image-left](/assets/fig_interfacemaps_edit.png){: .align-left style="width: 30%;"}
I construct lithosphere-scale structural images and models of the subsurface. For the
Pacific Northwest of North America, my colleagues and I built a structural model
of the subducting Juan de Fuca and Gorda tectonic plates using teleseismic receiver
functions -- a method to
image Earth's interior that uses earthquakes as an energy source, akin to reflection
seismics or ultrasound. The model indicates that the shape of the subducting plate is
controlled by the rigidity and competence of the terranes that make up overriding North
American continent. The subduction stratigraphy thickens down dip, suggesting that slab
material is underplated to the base of coastal North America.  The slab model and the
raw receiver functions are freely available from [*GFZ Data Services*<sup><i
class="fa-solid fa-arrow-up-right-from-square
fa-2xs"></i></sup>](https://doi.org/10.5880/fidgeo.2023.033). The corresponding
publication appeared in [*Geochemistry, Geophysics, Geosystems*<sup><i class="fa-solid
fa-arrow-up-right-from-square fa-2xs"></i></sup>](https://doi.org/10.1029/2023GC011088). 

To reconcile the intricate structure of the Pamir plateau with  paleogeographic
reconstructions, we conducted local seismic tomography. Together with the location of
intermediate depth seismicity, our tomograms reveal the eastern edge of an indenter of
the Indian continent that protrudes far north of the Himalaya and is likely responsible
for the rise of the protruding Pamir orogen. The 3D tomography and earthquake locations are
published through [*GFZ Data Services*<sup><i
class="fa-solid fa-arrow-up-right-from-square
fa-2xs"></i></sup>](https://doi.org/XXX). The corresponding
publication appeared in [*Geophysical Research Letters*<sup><i class="fa-solid
fa-arrow-up-right-from-square fa-2xs"></i></sup>](https://doi.org/10.1029/2021GL095413). 

### Software development

![image-left](/assets/fig_smc_hyb-prs_transp.png){: .align-left style="width: 40%;"} To
do inverse modelling of receiver functions, we overhauled Andrew Frederiksen's classic
code *Raysum* and ported it to the *Python* programming language. *PyRaysum* is highly
compatible with other research software, is fast, and comes with plotting functionality.
Get a stable version snapshot from [*Zenodo*<sup><i class="fa-solid
fa-arrow-up-right-from-square
fa-2xs"></i></sup>](https://doi.org/10.5281/zenodo.6095748), follow the project on
[*GitHub*<sup><i class="fa-solid fa-arrow-up-right-from-square
fa-2xs"></i></sup>](https://github.com/paudetseis/PyRaysum) and read the full article in
*Seismica*: [PyRaysum: Software for Modeling Ray-theoretical Plane Body-wave Propagation
in Dipping Anisotropic Media<sup><i class="fa-solid fa-arrow-up-right-from-square
fa-2xs"></i></sup>](https://doi.org/10.26443/seismica.v2i1.220 )

### Earthquake detection, location, magnitudes, re-location, focal mechanisms, moment tensors

The Pamir highlands of central Asia were struck by an earthquake sequence that lasted
over two years in 2015--2017. The initial magnitude 7.2 Sarez earthquake was followed by
two more shocks with a magnitude greater than 6 and several magnitude 5 earthquakes. The
sequence spread over an unusually large area, lasted long, and affected multiple,
dissimilar fault zones.

{% include video id="1QYi26a0bi_6K-72rk1jJrVtf-gIE7_uk" provider="google-drive" %}

To understand triggering of the subsequent earthquakes, we relocated tens of thousands
of fore- and aftershocks and determined dozens of earthquake moment tensors. The
earthquake locations show how the rupture areas of the later main shocks were
destabilized by foreshocks. Static stress transfer from one to the next large earthquake
was, however, low or even negative. More likely, fluids that have previously been imaged
to reside in the middle crust were mobilized by the initial main shock and triggered the
subsequent earthquakes.

All results are published in our article in *Geophysical Journal International*: [The
2015–2017 Pamir earthquake sequence: foreshocks, main shocks and aftershocks,
seismotectonics, fault interaction and fluid processes<sup><i class="fa-solid
fa-arrow-up-right-from-square fa-2xs"></i></sup>](https://doi.org/10.1093/gji/ggac473).
The earthquake catalog and moment tensors are available through *GFZ Data Services*:
[Earthquake and Moment Tensor Catalogs of the 2015-2017 Pamir Earthquake Sequence<sup><i
class="fa-solid fa-arrow-up-right-from-square
fa-2xs"></i></sup>](https://doi.org/10.5880/fidgeo.2022.007)

### Subduction processes
Subduction zones form beautiful landscapes around the so-called Ring of Fire that
surrounds the Pacific Ocean. They are defined as the geographic regions where the oceanic
tectonic plates are drawn beneath the continents by plate tectonics. The recycling
of rock, water, sediments and organic matter into Earth's mantle and their return to the
surface trough volcanism is a fascinating process that helps making Earth habitable in
countless ways.

![image-center](/assets/GJIancorp.png){:style="width: 80%;"}

With my colleagues, I investigated subduction processes taking place in the central
Andes of northern Chile from a seismological point of view. With a fully manually picked
earthquake catalog, we were able to define a triple seismic zone in the down-going
oceanic crust that extends to shallower depth than previously imaged. Seismicity of the
continental crust reaches the plate interface near the coast. In advance of the volcanic
arc, seismicity is constrained to the upper crust, where it's deepest occurrence defines
the brittle-ductile boundary. The results are published in [*Geophysical Journal
International*<sup><i class="fa-solid fa-solid fa-arrow-up-right-from-square
fa-2xs"></i></sup>](https://doi.org/10.1093/gji/ggu084)

![image-left](/assets/phasediagramG3-edit.png){: .align-right style="width: 60%;"}
The highly resolved earthquake catalog further allowed us to measure the in-situ rock
physical parameter of the P- to S-wave velocity ratio. The elevated value we found in
the lower seismicity zone indicates the presence of fluids, 40km deep, inside the
oceanic mantle. Through petrophysical and poroelastic modelling, we could demonstrate
that our observations are consistent with the presence of dehydrating vein networks,
similar to those found in outcrops certain serpentinite rocks. The correlation suggests
that serpentinite is dehydrating through veins in the lower band of seismicity of the
central Andean subduction zone. The corresponding article appeared in [*Geochemistry,
Geophysics, Geosystems*<sup><i class="fa-solid fa-solid fa-arrow-up-right-from-square
fa-2xs"></i></sup>]( https://doi.org/10.1029/2018GC007703).

With data from focal mechanisms and seismic moment tensors, we could also demonstrate,
how slab-pull is the driving force behind plate subduction in the working area. Only
where the down-going oceanic plate is coupled to the overriding continent, compression
dominates. The full article is accessible in [*Geophysical Research Letters*<sup><i
class="fa-solid fa-solid fa-arrow-up-right-from-square fa-2xs"></i></sup>](
https://doi.org/10.1029/2018GL078793).

![image-center](/assets/fps-rakeGRL-edit.png)
