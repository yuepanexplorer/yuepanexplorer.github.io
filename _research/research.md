---
layout: archive
title: "Research"
permalink: /research/
---

Before I start grad school, I sampled many fields of astrophysics. I put an emphasis on studying ultra-faint dwarf galaxies (<a href="https://en.wikipedia.org/wiki/Dwarf_galaxy#:~:text=Ultra%2Dfaint%20dwarf%20galaxies,-Ultra%2Dfaint%20dwarf&text=Unlike%20GCs%2C%20UFDs%20contain%20a,dark%20matter%2Ddominated%20systems%20known.">UFDs</a>) - one of the oldest, most dark-matter dominated, and chemically primitive stellar systems in the universe - because I was intrigued by their power to challenge
the <a href="https://en.wikipedia.org/wiki/Lambda-CDM_model">ΛCDM</a> paradigm. UChicago (where I did my undergrad) happens to have many experts in this field. My exploration into dwarf galaxies was encapsulated in three research projects, each of which attempted to answer a specific question.

How do dwarf galaxies quench?
---

I worked with Prof. <a href="https://astro.uchicago.edu/~andrey/">Andrey Kravtsov</a> and Dr. Christine Simpson on using the state-of-the-art cosmological hydrodynamical
simulation <a href="https://wwwmpa.mpa-garching.mpg.de/auriga/Auriga ">Auriga</a> to probe how dwarf galaxies quench (i.e., shut down their star formation) in simulations
across different mass scales. Our findings indicate that UV ionizing photons from the <a href="https://www.nsf.gov/news/special_reports/astronomy/epoch_reionization.pdf">epoch of reionization</a> primarily quench low-mass dwarf galaxies. In contrast, intermediate-mass dwarf galaxies are mainly quenched by environmental processes such as <a href="https://en.wikipedia.org/wiki/Ram_pressure">ram-pressure stripping</a>. High-mass dwarf galaxies largely remain star-forming as their substantial gravitational potential allows them to resist both stripping and early-universe quenching processes. We then juxtaposed our simulation results with several observations (the Satellies Around Galactic Analogs, or <a href="https://sagasurvey.org/">SAGA</a>; the Exploration of Local VolumE Satellites survey, or <a href="https://arxiv.org/abs/2203.00014">ELVES</a>) and discovered a consistent alignment. For more details, please refer to my <a href="https://arxiv.org/abs/2208.13805">paper</a>.

How can we more efficiently identify member stars of UFDs in observations?
---
Upon finishing the project above, I became curious about how observers manage to deal with ultra-faint and low-mass UFDs during their surveys. What surveys and techniques do we
need to study the resolved stellar population of Milky-Way (MW) UFDs? To explore this, I worked with Prof. <a href="https://kadrlica.github.io/">Alex Drlica-Wagner</a>, Prof. <a href="https://www.alexji.com/">Alexander P. Ji</a>, and Dr. <a href="https://www.anichiti.space/">Anirudh Chiti</a>. We used <a href="https://en.wikipedia.org/wiki/Photometry_(astronomy)#:~:text=Photometry%2C%20from%20Greek%20photo%2D%20(,light%20radiated%20by%20astronomical%20objects.">photometry</a> to identify member stars from three of the MW UFDs: <a href="https://en.wikipedia.org/wiki/Bo%C3%B6tes_I">Boötes I</a>, <a href="https://en.wikipedia.org/wiki/Bo%C3%B6tes_II">Boötes II</a>, and <a href="https://en.wikipedia.org/wiki/Segue_1">Segue I</a>.

Traditionally, observers use <a href="https://imagine.gsfc.nasa.gov/science/toolbox/spectra1.html#:~:text=The%20science%20of%20spectroscopy%20is,fast%20the%20material%20is%20moving.">spectroscopy</a> to identify member stars from their radial velocities and metallicities. However, one major issue with spectroscopy is that it primarily focuses on the central region of the system. Since spectroscopy is both extremely time-consuming and costly, observers typically apply it only to targets that are expected to yield significant results. The center is a good place to look because this region has a higher density of member stars. This approach leaves the outer region of UFDs largely unexplored. However, intriguing signatures that provide information about the evolutionary history of UFDs, such as <a href="https://en.wikipedia.org/wiki/Tidal_disruption_event">tidal disruption</a>, <a href="https://en.wikipedia.org/wiki/Galaxy_merger">merger events</a>, and <a href="https://astrobites.org/2017/04/12/breaking-wind/">supernova feedback</a>, are all found on the outskirts of UFDs. How to address this issue and access information on the outer region of UFDs? We turned to photometry for help!

We utilized the Dark Energy Survey Camera's (<a href="https://www.darkenergysurvey.org/the-des-project/instrument/the-camera/">DECam</a>) u-band to compute the photometric metallicity of each star within the camera's field of view. This is feasible because the u-band encapsulates the prominent <a href="https://www.aanda.org/articles/aa/full_html/2018/03/aa31926-17/aa31926-17.html#:~:text=The%20resonance%20doublet%20of%20Ca,investigate%20the%20photosphere%20and%20chromosphere.">Ca II K</a> metal absorption line, which can consequently be employed to establish a relationship between u-band brightness and metallicity. Following this, we applied an isochrone cut, proper motion cut, and photometric metallicity cut to select member stars of each UFD.

Upon mapping the spatial distribution of these member stars, we found indications that Boötes I may be undergoing tidal disruption by the Milky Way host. Conversely, Boötes II exhibited a more isotropic distribution of member stars, but it requires additional spectroscopy for confirmation. Furthermore, Segue I seemed to also be experiencing tidal disruption. Interestingly, we identified new member stars of Segue I extending to 5-6 half-light radii of the system. Paper forthcoming. Stay tuned for updates!


How does stochastic star formation affect global properties of dwarf galaxies?
---
For my honors thesis, I worked with Prof. <a href="https://astro.uchicago.edu/~andrey/">Andrey Kravtsov</a> on improving a semi-analytical galaxy evolution
model called <a href="https://ui.adsabs.harvard.edu/abs/2022MNRAS.514.2667K/abstract">GRUMPY</a>
(credit to the <a href="https://en.wikipedia.org/wiki/Grumpy_Cat">Grumpy Cat</a>). The specific improvement we made involved the implementation of stochastic star formation within dwarf galaxies in the model. While the model's generated dwarf galaxies demonstrated properties consistent with observations, one inconsistency stood out: the model did not produce any faint, blue dwarf galaxies that have been observed in surveys such as <a href="https://sagasurvey.org/">SAGA</a> and <a href="https://arxiv.org/abs/2203.00014">ELVES</a>. We hypothesized that introducing stochastic star formation into the model could lead some dwarf galaxies to intermittently form stars following the epoch of reionization, resulting in a blue color in the present day. This concept of stochastic star formation in dwarf galaxies is empirically driven. The star formation rate in such galaxies is primarily influenced by a few star-forming giant molecular clouds (GMCs), subject to small number statistics. In the original model, star formation was averaged over 2.5 Gyr—around one-fifth of the universe's age—thus failing to represent the bursty nature of star formation in dwarf galaxies. To rectify this, we applied the <a href="https://en.wikipedia.org/wiki/Fourier_transform">Fourier</a> transformation to the star formation history of each model galaxy, introducing power on small timescale variations to represent stochasticity. Contrary to our expectations, the introduction of stochastic star formation did not result in a population of faint, blue dwarf galaxies. However, introducing stochasticity in metallicity did influence some faint dwarf galaxies to appear bluer. This is because lower metallicity is typically associated with a bluer color. In line with our findings, researchers involved with the <a href="https://arxiv.org/abs/2203.00014">ELVES</a> survey also discovered that faint, blue dwarf galaxies in their survey demonstrated early-type morphology, indicating that their blue color wasn't a product of star formation. We'll be detailing these findings in a forthcoming paper. Stay tuned!


Other research explorations: cosmology
---
In the summer of 2022, I was selected as one of the <a href="https://www.daad.de/rise/en/rise-germany/">DAAD RISE Germany</a> scholars and visited the Ludwig Maximilian University of Munich. I worked with Dr. <a href="https://www.usm.lmu.de/people/stella/stella.html">Stella Seitz</a>, Anik Halder, and Laurence Gong. Our project focused on compressing the Dark Energy Survey's (<a href="https://www.darkenergysurvey.org/">DES</a>) Year 1 and Year 3 two-point correlation function (<a href="https://ned.ipac.caltech.edu/level5/March12/Coil/Coil2.html#:~:text=(r)%2C%20which%20traces%20the,as%20a%20function%20of%20scale.&text=(r)%20are%20generally%20performed%20in,units%20of%20h%2D1%20Mpc.">2PCF</a>) data. Identifying a method to efficiently compress this vast dataset without losing critical information can enhance the way we store and manage the data for further analysis. This approach has the potential to be extended to other large datasets in the future. Stay tuned for more information!


Non-astro research exploration: machine learning!
---
In the summer of 2023, I was selected as one of the <a href="https://lambdafoundation.org/">Lambda scholars</a> to work at Mila, the Quebec AI Institute. Currently, I'm collaborating with Prof. <a href="https://mila.quebec/en/person/yashar-hezaveh/">Yashar Hezaveh</a> and Prof. <a href="https://phys.umontreal.ca/repertoire-departement/professeurs/professeur/in/in31242/sg/Laurence%20Perreault-Levasseur/">Laurence Perreault-Levasseur</a> on an ambitious project. Our goal is to train a neural network capable of transforming low-resolution images into high-resolution versions. This endeavor has substantial implications for astronomy, specifically in the field of strong gravitational lensing. In this domain, different sections of the source object are magnified to varying degrees, making it challenging to accurately represent the source image using a uniform resolution.














































