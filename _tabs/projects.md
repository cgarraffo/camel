---
icon: fas fa-folder
order: 3
---

[//]: # (Past, current, proposed)
# Event Horizon Telescope - IACS projects:

## The Parametrization of M87 Black Hole: A Deep Learning Approach with EHT Data.
### Tao Tsui, Pavlos Protopapas, Cecilia Garraffo, Christian Framm and Sheperd Doeleman

## Modeling the scattering in Sgr A* using neural networks
### Paul Tiede, Lindy Blackburn

## Modeling noise due to accretion physics
### Paul Tiede, Lindy Blackburn

## Characterization of black holes from EHT images using deep learning
### Keerthi Kunnumkai, Cecilia Garraffo and Pavlos Protopapas

# CfA - Southampton projects:

Unsupervised Machine Learning for the Classification of Astrophysical X-ray Sources
Victor Samuel Perez-Diaz, Juean Rafael Martinez-Galarza, Alexander Caicedo-Dorado and Raffaele D'Abrusco

Mapping X-ray variability curves]{Mapping the X-ray variability curves of GRS 1915+105 with machine learning
Benjamin J. Ricketts, James F. Steiner, Cecilia Garraffo and Ronald A. Remillard

Semi-Supervised Autoencoder for Parameter Prediction from Black Hole X-Ray Binary Spectra
Ethan Tregidga, Jack Steiner and Cecilia Garraffo

Super Resolution for the Line Emission Mapper Probe
Ethan Tregidga, Jack Steiner and Cecilia Garraffo

## UBA - CfA - IACS projects:

Cosmologically Informed Neural Networks to Solve the Background Dynamics of the Universe
Augusto T. Chantada, Susana J. Landau, Pavlos Protopapas, Claudia G. Scoccola and Cecilia Garraffo

## CfA - IACS projects:

StelNet: Higherarchical Neural Netwoirk for Automatic Inference in Stellar Characterization
Cecilia Garraffo, Pavlos Protopapas, Jeremy J. Drake, Ignacio Becker and Phillip Cargile

## CfA Proposals - accepting collaboration:

### PI: Razieh Emami

Recent studies show that MW galaxies from the cosmological simulations of the TNG are twisted. What drives the galaxy rotation remains elusive and must be connected to the galaxy evolution and the impact of the mergers. A first look at the redshift evolution of galaxies demonstrates that the galaxy type is changed over the time and there are also some levels of the noise there. In this work, we aim to use some machine learning approach to trace the galaxy shape evolution over the cosmic time and figure out the main drivers of the galaxy rotation. References can be found here: \href{https://ui.adsabs.harvard.edu/abs/2021ApJ...913...36E/abstract}{1}, \href{https://ui.adsabs.harvard.edu/abs/2021ApJ...918....7E/abstract}{2}, \href{https://arxiv.org/abs/2210.01051}{3}.

## Painting gas onto dark-matter-only simulations with neural nets

### PI: Urmila Chadayammuri

As we understand it today, most of the matter in the Universe is dark, i.e. it only interacts with anything else via gravity. On the other hand, everything that we see is normal, or baryonic, matter. In galaxy clusters, large groups of thousands of galaxies, the space between galaxies is filled with a plasma (ionised gas). This plasma does know about the gravity of the dark matter in the region, but also experiences other physics, like cooling and heating, which are far more complicated. We can test different models of dark matter by looking at the statistics of galaxy clusters. Simulating large numbers of these with all the gas physics is currently computationally infeasible. Instead, we have large suites of dark-matter-only simulations, which only have to solve the equation of gravity, and then smaller simulations which simulate all the gas physics as well but don't have enough statistics for cosmology. I would like to teach ML to "learn" from the smaller simulations how to "paint" gas onto the dark-matter-only simulations. 
My input is 2D maps of the projected dark-matter quantities on the one hand, and corresponding 2D maps of the gas on the other. After training, the model should be able to read in other maps of dark matter, and predict what the gas would look like (i.e. what telescopes would see). Currently I am struggling with getting the neural net to capture the smallest, brightest regions.

## Galileo Project

### PI: Avi Loeb
Developing sensor systems and software to detect, track and analyze UAP and `Oumuamua-like ISOs, whatever they maybe, using automated detection and tracking of aerial anomalies

## Classifying Variable Stars from SDSS-IV

### PI: Paul Green

The SDSS-IV Time Domain Spectroscopic Survey (TDSS) obtained SDSS optical spectroscopy for about 11000 variable stars.  We have characterized numerous variability attributes from ZTF light curves, absolute magnitudes and Galactic position from Gaia, and the spectral type from SDSS.  We want to classify as many variables into physical types as possible.  We are developing training sets from the literature and from our own visual inspection.  About half the stars show periodic variability and are most easily classified.  Non-periodic variable stars may be irregular, poorly-sampled, or exotic.

## Reinforcement learning for optical system alignment

### PI: Qi Feng

The prototype Schwarzschild-Couder Telescope has two mirror dishes with 48 primary mirror panels and 24 secondary. Each panel is controlled with 6 actuators for alignment. A total of 432 input for all actuators controls the alignment with a goal to minimize the optical PSF (characterized by the rms of the images of stars). This problem is, in principal, suitable for reinforcement learning, as the reward is well-defined. However, the control/action space is very large and continuous, which could be a problem due to the inefficiency of reinforcement learning algorithms. It would be nice to discuss the possibility of applying reinforcement learning to the alignment problem and perform some proof-of-concept simulations to verify the feasibility. 

## Calculation of Air Mass Factor for Air Quality of observations using UV-VIS spectrometers

### PI: Gonzalo Gonzalez Abad

Using remote sensing from satellites we can prove the Earth's atmosphere to gain information about the distribution of several pollutants. Depending on their vertical distribution, the spectral region(s) at which they absorb/emit/scatter light, we can obtain one or more pieces of information. Using UV-VIS radiation, usually all we can obtain is the integrated concentration on the line of site. To transform this information to more useful values for the atmospheric chemistry and air quality communities we rely on radiative transfer calculations. These calculations have two main problems:
1. They are computationally expensive
2. They rely quite often on prior information from weather and chemistry atmospheric models.

The goal of this project is to speed up/substitute the AMF calculation and become more independent of prior model information by training a model of AMF(s)/atmospheric scattering properties on geophysical values retrieved from multiple satellites and spectral ranges.

## Detecting the most distant galaxy groups with the Line Emission Mapper
### PI: Gerrit Schellenberger

Most of the galaxies in the universe are found in galaxy groups, which are gravitationally bound structures not only containing the galaxies, but also a hot, X-ray emitting gas. Galaxy groups started to form in the universe when its size was only a third or even smaller. While galaxy groups are often assumed to have a fine-tuned balance of the gravitational potential and the thermal pressure of the hot gas, the effects of star formation in the galaxies, or outbursts from the central supermassive black hole can harm this equilibrium. The amount of these non-gravitational effects is not yet understood. Since star formation is known to be much more dominant in very distant galaxies, these effects will also be imprinted in distant galaxy groups. However, only a few very distant galaxy groups are even known so far due to the lack of instrumental sensitivity. 
The Line Emission Mapper (LEM) probe mission concept will have exceptionally high spectral resolution, and is able to resolve individual emission lines from these distant galaxy groups. This will lead to many newly detected groups, especially at higher redshift. Machine learning techniques are uniquely suited to reliably detect these emission lines, which are shifted according to the distance of the object. 
A ML algorithm should be designed and trained through simulated mock observations to detect the known emission lines which are shifted to unknown energies due to the cosmological redshift. The individual lines are not clearly visible, but a stacked set of lines should be used to identify the object more significantly. Furthermore, the spatial information - the expected extent of the galaxy group - should be included when defining a detection. Complications arise when including the Milky Way foreground emission, or bright (continuum) point sources at the centers of the galaxy groups resembling the central AGNs. The goal is to define a realistic detection probability and false detection rate depending on galaxy group parameters such as its distance and mass. 


## DSCOVR Faraday Cup error mitigation
### PI: Michael Stevens

The instrument that monitors the solar wind for NOAA space weather forecasting suffers from a grounding fault. This fault results in parasitic oscillations that contaminate the science data. Particle energy spectra are superposed with noisy signals of varying wavelength, often having width on the order of the target peak width, and often having amplitudes on the order of the peak amplitude. 

This instrument is past it's intended lifetime, however, NOAA continues to rely on these data on a continuous basis until the follow-on mission goes into operations (~3 years from now).

It is highly desirable to get *some* estimate of the solar wind proton peak under all conditions, but it is highly undesirable to misattribute the solar wind proton peak to an oscillation.

We are working to optimize data return under those constraints and ideally to provide reliability indicators.

There are other spacecraft providing similar measurements [reliably] from similar vantage points in space. We are considering the extent to which they can be used as a proxy for ground truth. 

Based on that, we could envision training classifiers to (a) signify the presence and severity of the oscillations and (b) estimate the reliability of the solar wind parameters. We could also envision a persistence model where a reliable measurement is incorporated as a prior then updated or not updated on subsequent measurements based on these classifiers. We entertain the possibility of using NN regression to estimate the peak parameters directly under noisy conditions.

## MethaneSAT cloud filter
### PIs: Kelly Chance & Xiong Liu

We're developing an algorithm that shall use ML techniques to screen for clouds in remote sensing image data To some extent, cloud screening in our images is simply a pattern recognition task, which seems predestined for a machine learning approach
