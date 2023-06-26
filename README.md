[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc/4.0/) 

# Rowhammer Implementation on rpi3

Simple Rowhammer attack PoC for Raspberry Pi 3B+

## Usage
* Download `rowhammer.c` on the Raspberry Pi with `git clone https://github.com/developedby/rowhammer_rpi3.git` or your preferred method.
* Compile with `gcc rowhammer.c -o rowhammer`.
* Execute with `sudo ./rowhammer`, and follow the instructions of the CLI interface.

This code is based on [https://github.com/0x5ec1ab/rowhammer_armv8], trimmed down to only the essential parts. It also has some slight modifications to work on Raspberry Pi instead of their board.

*This was only tested on the Raspberry Pi 3B+ and will likely not work on boards with different memory chips.*

## Supporting material

* **Lecture - Rowhammer.pdf:** an introductory lecture on rowhammer* **Lecture - Introduction to rowhammer.pdf:** an extensive overview of the rowhammer attack
* **Lab - setup.pdf:** a set of solved exercises to understand the attack using the code published in this repository.
* [A Youtube video showing the implementation of the attack](https://www.youtube.com/watch?v=RxVXr_Hvu-Y) 

## Authors

This material was initially developed as part of an assignment for the Operating Systems for embedded systems course delivered at Politecnico di Torino by Prof. Stefano Di Carlo during the academic year 2022/20023. 

Credits for the preparation of this material go to:

* [Nicolas Abril](https://github.com/developedby)
* [Matteo Isoldi](https://github.com/bOhYee)
* [Massimiliano Di Todaro](https://github.com/mditodaro)
* [Diego Porto](https://github.com/akhre)

Original code by VandySec Group (https://github.com/0x5ec1ab/rowhammer_armv8). It is proprietary, but following Github's [Terms of Service](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service#5-license-grant-to-other-users), any user is allowed to view and fork public repositories inside Github.


