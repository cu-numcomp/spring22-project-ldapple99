# Coral: A Brief Overview

## Links
 * [JSS - Coral: a parallel spectral solver for fluid dynamics and partial differential equations](https://joss.theoj.org/papers/10.21105/joss.02978)
 
 * [Coral GitHub Repository](https://github.com/BenMql/coral)

## What is Coral?
Created by Benjamin Miquel at the Université Paris-Saclay, CEA, CNRS, Service de Physique de l’Etat Condensé (University of Paris-Saclay, CEA, CNRS, Service of Condensed Matter Physics), Coral is a speedy and effiecent time-stepper for solving a wide range of partial differential equations, for example the Navier-Stokes equations below which make up a large portion of fluid dynamics. 

![image](https://user-images.githubusercontent.com/54420393/161450734-3defca71-0cab-44af-ab84-f6d70493aa52.png)

The image above is taken from the [Navier-Stokes equations Wikipedia page](https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_equations)


## What is Coral trying to solve?

Coral was originally designed to help study **Co**nvection in **Ra**pidly rotating **L**ayers (**CO RA L**) in a speedy matter using both Fourier Series and Chebyshev polynomials to accurately and quickly model various aspects to fluid mechanics (for example density, temperature, salinity, magnetic field, velocity, etc).  Although now, it is unique in that it can be used to model various other elements that rely on homogeneous quadratic partial differential equations. Coral is special in that it uses a quasi-inverse technique which allows the usage of a large number of Chebyshev Polynomials which allowed the ability for the team to resolve thin boundary layers that are quite common in turbulent flows without losing a large amount of accuracy. 

## Who are the stakeholders of Coral?

 Coral was written by Benjamin Miquel who is a researcher at the Université Paris-Saclay, CEA, CNRS, Service de Physique de l’Etat Condensé (University of Paris-Saclay, CEA, CNRS, Service of Condensed Matter Physics), where it was originally used to help study the **Co**nvection in **Ra**pidly rotating **L**ayers (**CO RA L**) in fluid mechanics. Mostly written in Fortran on a [GitHub Repository](https://github.com/BenMql/coral), Coral has expaneded and is now commonly used to model various other components that use homogeneous quadratic partial differential equations where it is designed for both  students and researchers with little to no coding experience to use. For this reason, Coral has very much so positively impacted the scientific community researching a wide range of physics (fluid mechaics, theromodyamics, condensed matter, etc).

## What are the Metrics and Features of Coral?
  * How do concepts like accuracy, conditioning, stability, and cost appear?
  * If the software is fast, how is "fast" defined?
  * If the software is accurate, what does accuracy mean? Could you make a plot, say accuracy vs cost? How would you label the axes to make it relevant to    a stakeholder?
  * Would different stakeholders want different axes (because they care about different things)?
  * Are there modeling decisions made in the interest of good conditioning? Are there algorithmic choices made for stability?
Some of the tests that were done for Coral include...

## Question I have about the Coral Software
I wonder....

## A potentially intresting experiment using Coral
During my research into Coral, I started wondering about what if....
