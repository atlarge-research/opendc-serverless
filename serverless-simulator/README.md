<h1 align="center">
  <a href="http://opendc.org/">
    <img src="misc/artwork/logo.png" width="100" alt="OpenDC">
  </a>
  <br>
  OpenDC Serverless
</h1>
<p align="center">
Collaborative Datacenter Simulation and Exploration for Everybody
</p>

## Introduction
This repository hosts the public source code of the serverless simulation component of the [OpenDC](https://opendc.org) project. This component is responsible for modelling and simulation of Function-as-a-Service platforms and their components. 

## Documentation

Relevant code file path: opendc-serverless/serverless-simulator/opendc/opendc-serverless/

Experiment configurations contained in: opendc-serverless/serverless-simulator/serverless/

Modules:
* compute: encapsulates logic related to function management (containers, deployment, request routing)
* core: Contains general use components
* experiment: experimentation framework that allows for parralel execution of different scenarios
* monitor: encapsulates logic related to monitoring simulation statistics
* resource: encapsulates logic related to virtual machine and container management

To use the Experiment Framework, run ExperimentFramework.kt and supply the 3 following elements in order as arguments.
* Path Directory of trace files
* Path Directory of experiment configurations
* Seed

NOTE: Before you can run the simulator, install R and Rserve on your computer and start an Rserve instance on port 1200 


TODO

## Getting Started
TODO

### License
The OpenDC simulator is available under the [MIT license](https://github.com/atlarge-research/opendc-simulator/blob/master/LICENSE.txt).
