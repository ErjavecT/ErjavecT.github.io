---
title: "Current Research at UC Davis"
permalink: /research/
layout: single
classes: wide
taxonomy: markup
entries_layout: grid
date:
separator: true


sidebar:

  - title: "Selected Publications"
  - text: <hr class="rounded_blk">
  -   text: "[A Compound Poisson Generator Approach to Point-source Inference in Astrophysics](https://iopscience.iop.org/article/10.3847/1538-4365/ac5cb7) *Collin, G., Rodd, N., Erjavec, T., and Perez, K.* The Astrophysical Journal Supplement Series. *2022*"
  - text: <hr class="rounded_grey_sm">
  - text: "[Passivation of Si(Li) detectors operated above cryogenic temperatures for space-based applications
](https://www.sciencedirect.com/science/article/pii/S0168900220314121?via%3Dihub) *Saffold, N. Rogers, F. Xiao, M. Bhatt, R. Erjavec, T. Fuke, H. Hailey, C.J. Kozai, M. Kraych, D. Martinez, E. et al.* NIM A. *2021*"
  - text: <hr class="rounded_grey_sm">
  - text: "[Large-area Si(Li) detectors for X-ray spectrometry and particle tracking in the GAPS experiment
](10.1088/1748-0221/14/10/P10009) *Rogers, F. Xiao, M. Perez, K.M. Boggs, S. Erjavec, T. Fabris, L. Fuke, H. Hailey, C.J. Kozai, M. Lowell, A. et al.* Journal of Instrumentation. *2019*"
  - text: <hr class="rounded_grey_sm">
  - text: "[Fabrication of low-cost, large-area prototype Si(Li) detectors for the GAPS experiment
](https://doi.org/10.1016/j.nima.2018.07.024) *Perez, K. Aramaki, T. Hailey, C.J. Carr, R. Erjavec, T. Fuke, H. Garvin, A. Harper, C. Kewley, G. Madden, N. et al.* NIM A *2018*"
  - text: <hr class="rounded_grey_sm">

---


<div class="div-1">
<br>

<p><img src="/assets/images/logos/ucdavis.svg" width="200px" style="float:right"> At UC Davis, I work under Prof. Emilija Pantic whose lab specializes in Liquid Argon(LAr) Time-Projection Chambers(TPC). My time is spent between two major experiments: Darkside20k and DUNE.</p>

<!-- <h2 class="decorated" style="display:inline"> <span>DarkSide-20k </span>  <img src="/assets/images/logos/darkside.png" style="float:right;position:relative;z-index:1;display:inline-block" width="130px"></h2>
<hr style="height:10px; visibility:hidden;" /> -->
<h2> DarkSide-20k <img src="/assets/images/logos/darkside.png" style="float:right" width="130px"> </h2>

<p> <a href="https://www.lngs.infn.it/en/darkside">DarkSide-20k</a>,
 located at Laboratori Nazionali del Gran Sasso in Italy, is a dual-phase LAr TPC whose main goal is to directly detect WIMP dark matter.  The main working priciple of a LAr TPC is as follows.</p>


<figure style="width: 400px" class="align-right">
  <a href="/assets/images/research/2Phase_Poehl.png" title="2-Phase TPC" alt=" foo">
  <img style="border: 1px solid #000" src="/assets/images/research/2Phase_Poehl.png" alt=""></a>
  <figcaption style="text-align: center"> Working principal of a dual-phase argon TPC. Image by M. Poehlmann</figcaption>
</figure>

<p>Inside a volume is held liquid argon through which permeates a uniform electric field. If a dark matter candidate interacts through a nuclear or electronic recoil, it could deposit energy either through atomic or electron excitation, it produces UV light and/or electrons.  The light is collected using an array of silicon photomultipliers (SiPMs), providing timing and position resolution. Electrons that are liberated then drift along the E field towards the top of the detector, first inducing charge in a wire-plane, above which sits a small layer of GAr (hence the dual-phase). When electrons enter the gaseous region, they release a second pulse of light which is then collected by the SiPM array. Such an experimental setup allows us to reconstruct position and timing information, direction included, and also the total energy of the event.</p>


<p>The subsequent detection or lack thereof informs the parameter space in which WIMP dark matter may exist. It is evident that if WIMPs exist. they interact exceptionally rarely, meaning that we could just wait for a longer period of time, but sadly human lifespans are not in the hundreds of years  The nice thing is that the probability of an interaction is proportional to the amount of stuff that it could bump into, so we can just make our experiments larger! In the case of Darkside 20k, we are going to be using 20 tons of LAr. However, having larger and larger experiments come with all sorts of engineering challenges. One particular one is maintaining a reasonably strong drift field over longer distances, meaning we need to employ even larger high voltages.</p>


<p>Currently,the collaboration is focused on research and development and validation of the design and concepts for the full-scale detector. Our lab is responsible for the delivery of high-voltage (HV), which sets up the electric drift field. In order to carry the high voltage, we are using a purely plastic coextruded coaxial cable with a semi-conductive central core. Much work in lab is focused on how to properly integrate this cable into the cryostat. </p> </div>
<hr class="rounded_grn">
<div class="div-1" markdown="1">
<h2> DUNE  <img src="/assets/images/research/dune_logo.png" style="float:right" width="150px"> </h2>
<p style="margin-right: 160px"><a href="https://www.dunescience.org/">DUNE </a>is a long-baseline neutrino experiment which aims to pin down the nature of ghostly particles called neutrinos. Neutrinos are very hard to detect because they only interact via the weak force - and well, gravity, but until we become a Class III civilization, good luck with that. Now because they are so hard to observe, there are many parameters that are not well-constrained or even known at all. DUNE first starts as a neutrino beam at FermiLab, just outside of Chicago. The beam travels 1300 through the earth and then are detected in an underground laboratory using four single-phase TPCs in South Dakota.</p>

<figure style="" class="">
    <img src="{{ site.url }}{{ site.baseurl }}/assets/images/research/DUNE.png" alt="">
    <figcaption style="text-align: center"> Schematic of the DUNE experiment. Neutrinos are created at FermiLab, travel 800 miles underground, and then are detected in an abandoned gold mine in South Dakota.</figcaption>
</figure>

<p>In rare event searches, one of the most important things is to understand the signal we are trying to detect, our detector's response, and the backgrounds that we don't want but will inevitably detect nonetheless. A neutrino, when interacting with an argon nucleus will interact weakly through the exchange of a neutral ($Z^0$) or charged ($W^{\pm}$) boson. </p>

<figure class="half" style="display:flex;align-items: center;justify-content:center">
    <img style="height: 300px; width: auto" src="/assets/images/research/W_feyn.png">
    <img style="height: 280px; width: auto" src="/assets/images/research/Z_feyn.png">
    <figcaption style="text-align: center">Two of many possible neutrino interactions. Left shows anti-electron neutrino elastic scattering and right show a NC interaction, which deposits energy and puts the nucleon into an excited state  </figcaption>
</figure>

<p>At these energies, we can have simple elastic scattering all the way to creating hadronic resonances. Specifically, in approximately 16% of Charged Current(CC) events, a neutron is created. The neutrons, as their name implies, are neutral, meaning they do not interact electromagnetically and thus produce no light or electrons which are the primary detection modes in a TPC. They can interact via recoils, but the energy deposit is small and below DUNE's energy resolution. </p>
<figure style="width: 400px" class="align-center">
<img style="border: 2px solid #000" src="/assets/images/research/n_frac.png">
<figcaption style="text-align: center"> Breakdown of branching ratios from a 3.5MeV $\nu_e$ CC reaction. <em> Courtesy of S. Gardiner </em></figcaption>
</figure>

<p> For example, a neutron around 100 keV, a recoil against an argon nucleus will lose approximately 5% of its kinetic energy. Eventually a neutron, after bouncing around in the detector, will capture on an argon nucleus and release gammas with a fixed energy. This light we can detect, but it can be far away from the vertex of the interaction that produced the neutron. It then follows that in order to reconstruct the energy of the original event, we need to be able to understand how neutrons transport through liquid argon, which can be described by the *total cross section*, $\sigma_{tot}$, in argon.</p>



<p>It so happens that there is an antiresonance feature in the $\sigma_{tot}$ where the cross section is predicted to be very small. However, a previous measurement of $\sigma_{tot}$ in that region may have not been sensitive enough, and gives a cross section about an order of magnitude higher than the model-predicted value. This gives a mean interaction length of 30 meters and 4 meter, respectively, of which the former is roughly the dimension of the DUNE far detector! Trying to reconstruct event energies and having to comb through the entire detector volume is untenable, so therefore we need to resolve this discrepency. This leads to the DUNE ancillary experiment, the Argon Resonance Transport Interaction Experiment (ARTIE), which was performed at Los Alamos National Laboratory (LANL) and composes the majority of my dissertation.</p>

<figure style="width: 500px" class="align-center">
  <img style="border: 2px solid #000" src="/assets/images/research/winters_artie.png" alt="">
      <figcaption style="text-align: center">The approx. order of magnitude difference between a model-predicted cross section (black) and a previous experiment (blue).   </figcaption>
</figure>


<h3> Argon Resonance Transport Interaction Experiment (ARTIE)</h3>

<p>ARTIE was an experiment done at Los Alamos National Laboratory in 2019 using the neutron beam at their LANSCE facility. The working principal of ARTIE was a Time Of Flight (TOF) experiment, where we create neutrons and then time how long it takes for them to traverse some distance where they pass through a target and then interact with a detector at the end of said distance. Since we know both the time it took and the distance the neutrons travelled, we can easily calculate their energy via kinematics. Whether or not the neutrons interact depends enetirely on their energy, so we can then bin the neutrons as a function of energy and calculate their cross section.  </p>

<figure style="width: 750px" class="align-center">
  <img style="border: 2px solid #000" src="/assets/images/research/tof.png" alt="">
      <figcaption style="text-align: center"> A diagram showing the principle of a TOF experiment   </figcaption>
</figure>


<p>The target consisted of a 1.6 meter long stainless steel tube filled with liquid argon, with a nominal target density of 3.3 atoms/barn. We ran in 2019 over two weeks. We recently have submitted for publication, preprint on the arXiv is located <a href="https://arxiv.org/abs/2212.05448"> here </a> </p> </div>

<hr class="rounded_grn">

<h1>Past Research</h1>

<div class="div-1" markdown="1">
<h2>Massachusetts Institute of Technology (2016-2018) <img src="/assets/images/logos/mit.svg" style="float:right" width="120px"></h2>


<p style="margin-right: 160px">At MIT, I worked under <a href="https://physics.mit.edu/faculty/kerstin-perez/">Prof. Kerstin Perez </a>, who at the time was an incoming professor. Her lab specialized in high-temperature (relatively) lithium-drifted silicon (SiLi) detectors for x-ray spectroscopy. These detectors are the basis for the <a href="https://gaps1.astro.ucla.edu/gaps/">General Antiparticle Spectrometer </a> (GAPS), which is a balloon-borne experiment searching for secondary particles from dark matter annihilation, particularly anti-deuterons, ($\overline{D}$).</p><img src="/assets/images/research/gaps_logo.png" style="float:right" width="120px">

<figure style="width: 500px" class="align-center">
  <img style="border: 2px solid #000" src="/assets/images/research/gaps_princ.png" alt="">
    <figcaption> The GAPS experiment uses layers of Si(Li) detectors to track charged cosmic rays. Shown is a diagram of an anti-deuteron interacting with the detector. The anti-deuteron will form an exotic atom, taking the place of an electron, until it annihilates with the nucleus creating signature x-rays and charged pions.</figcaption>
</figure>

<p>Prof. Perez was also highly involved in the <a href="https://www.nustar.caltech.edu/">NuSTAR </a> x-ray telescope, with particular interest in xray signals from the self-annihilation of dark matter particles. Since the Milky Way is a pretty busy place, there are many sources of xrays and thus these need to be accounted for and subtracted away so that we can characterize whatever signals may remain. One particular problem of interest was to set limits and constrain the population of unresolved point sources - meaning xray sources that are smaller than the effective resolution of the telescope. This can be achieved through the modification of Non-Poissonian Template Fitting (NPTF), which uses Bayesian methods to set population density likelihoods. Tailoring this to NuSTAR is problematic, as NuSTAR images are tiled and superimposed one on top of another, with distortions due to NuSTAR's Point Spread Function (PSF). To overcome this, the NPTF method was modified, resulting in a Compound Poisson Generator approach</p> </div>
<hr class="rounded_grn">

<div class="div-1" markdown="1">

<h2>Ohio State University (2014-2016) <img src="/assets/images/logos/osu.svg" style="float:right" width="130px"></h2>


<p>At Ohio State, I jumped around a few labs until I began working for <a href="https://ccapp.osu.edu/people/connolly.171">Prof. Amy Connolly </a>. Prof. Connolly specializes in ultra-high energy neutrinos which result from some of the most energetic events in the Universe. In particular, her group focused on experiments analyzing radio signals produced from neutrino interactions with matter, namely the <a href="https://www.phys.hawaii.edu/~anita/new/index.html">Antarctic Impulse Transient Antenna </a> (ANITA) and the <a href="https://ara.wipac.wisc.edu/home)">Askaryan Radio Array </a> (ARA). For the latter, I worked developing front-end electronics meant to variably condition the signals from the ARA antennas in-situ.</p> </div>
<hr class="rounded_grn">
<div class="div-1" markdown="1">

<h2>REU at MIT Haystack Observatory (2014)  <img style="border: 1px solid #000" src="/assets/images/logos/haystack.jpeg" style="float:right;border: 1px solid #000" width="120px" Padding="0px,0px"></h2>


<p>In 2014 I was awarded an REU at the <a href="https://www.haystack.mit.edu/">MIT Haystack Observatory </a> where I worked under <a href="https://en.uit.no/ansatte/juha-pekka.vierinen">Dr. Juha Vierinen </a>. Dr. Vierinen's expertise lay primarily in radar analysis, particularly towards atmospheric science. One specialty of Haystck lays in studying the ionosphere, which is the outermost layer of Earth's atmosphere consisting primarily of ions and their free electrons due to the exposure to the ionizing UV radiation from the Sun. The electron density in the ionosphere is such that it reflects radio waves, depending on their plasma frequency.</p>
<p>The ionosphere is not uniform, neither radially nor azimuthally. Electron density can vary depending where you are in the ionosphere as well in time, due to solar irradiance or solar weather. The effect of solar storms on the ionosphere is an active area of research and is important because of the influence that the ionosphere has on communications, both here on Earth and our ever-growing collection of orbiting satellites.</p>
<p>A major limiting factor in ionopsheric research is that of <em>resolution</em>. Many ionosondes are large (~10s of meters), unwieldy, and expensive, thus they cannot be deployed in dense networks, so it is difficult to look at broad ionospheric topography. My project at Haystack was to prototype and small, low-cost ionosonde for mass deployment. During the summer I built a variably-tuned loop antenna for the 10-70MHz band, and obtained ionospheric echoes. No more than 3 feet across, the antenna and associated electronics could be carried by a single person.</p>

<figure class="half" >
  <img style="height: 380px; width: auto; border: 1px solid #000" src="/assets/images/research/haystack_echo.png" >
  <img style="height: 380px; width: auto; border: 1px solid #000" src="/assets/images/research/haystack_loop.jpg">
  <figcaption style="text-align: center"> Left: An ionospheric reflection using the loop antenna, with chirp at 5.98Mhz, showing an X (top) and O (bottom) mode trace. Notice the doppler shift due to a gps clock mismatch! Right: the transmit antenna</figcaption>
</figure>

<hr class="rounded_grn">
<div class="div-1" markdown="1">

## REU at Cornell University (2013)

<p>In 2013, I spent a summer at Cornell working under <a href="https://www.engr.cornell.edu/faculty-directory/james-r-engstrom"> Prof. James Engstrom </a> at the <a href="https://www.cnf.cornell.edu/">Cornell Nanoscale Facility </a>. During my internship, I undertook a project by which to simultaneously deposit tantalum nitride (TaN) on silicon and not copper. In the creation of microchips, many individual patterning steps are taken in order to form the nanoscopic cicuits layer by layer. My project aimed to reduce the number of these steps (and therefore save time and $$$) by taking advantage of differing adsorption strengths of TaN on various substrates.</p> </div>

</div>