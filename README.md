# Fault Detection in Wastewater Treatment Plants: Application of Autoencoders with Streaming Data
The objective of this work is to use Artificial Neural Networks (ANN), more specifically Autoencoders, to design a real time fault 
detection system for the dissolved oxygen (DO) sensor, present in the aeration system of the biological reactor of a 
wastewater treatment plant (WWTP).

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Results](#Results)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information

- The work described here had its origin in the elaboration of the dissertation for the conclusion of the master's course in Data Science at the [Faculty of Sciences](https://sigarra.up.pt/fcup/pt/web_page.inicial) of the [University of Porto](https://www.up.pt/portal/pt/) - Portugal. The dissertation can be found [here](https://repositorio-aberto.up.pt/bitstream/10216/146754/2/597464.pdf). 

- This work originated a paper that was presented at the 7th Workshop on Data Science for Social Good - [SoGood 2022](https://sites.google.com/view/ecmlpkddsogood2022/home?pli=1), 19-23 September 2022, in Grenoble, France. This paper can be found [here](https://github.com/RodrigoSalles/WWTP_Fault_detection/blob/master/SoGood_2022.pdf).

- The objective of this work is to develop a real time fault detection system for the DO sensor of a WWTP biological reactor. 

- To better evaluate the performance of the Autoencoders three scenarios were considered with variations in the order of appearance, duration and intensity of failures.

- ANN models used for fault detection:
   * Convolutional Autoencoder
   * Long short term memory (LSTM)
   
- Faults implemented for autoencoder testing:
   * Drift 
   * Bias
   * Precision degradation
   * Spike
   * Stuck


## Technologies Used
- Python - version 3.8.8
- Keras - version 2.6.0
- TensorFlow - version 2.6.0
- Benchmark Simulation Model no. 2 (BSM2)


## Results
* Fault Detection Result Example - Convolutional Autoencoder
<img src="Figures/f5.png"  width="800" height="300">

* Fault Detection Result Example - Convolutional Autoencoder - Drift fault.
<img src="Figures/f6.png"  width="800" height="300">


## Setup
What are the project requirements/dependencies? Where are they listed? A requirements.txt or a Pipfile.lock file perhaps? Where is it located?

Proceed to describe how to install / setup one's local environment / get started with the project.


## Usage
How does one go about using it?
Provide various use cases and code examples here.

`write-your-code-here`


## Project Status
Project is: _in progress_ / _complete_ / _no longer being worked on_. If you are no longer working on it, provide reasons why.


## Room for Improvement
Include areas you believe need improvement / could be improved. Also add TODOs for future development.

Room for improvement:
- Improvement to be done 1
- Improvement to be done 2

To do:
- Feature to be added 1
- Feature to be added 2


## Acknowledgements
Give credit here.
- This project was inspired by...
- This project was based on [this tutorial](https://www.example.com).
- Many thanks to...


## Contact
Created by [@flynerdpl](https://www.flynerd.pl/) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
