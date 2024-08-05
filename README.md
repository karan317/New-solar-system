# Data Science Simulation: Introducing a Second Sun to the Solar System Using Python

## Overview

This project simulates the introduction of a second star to our Solar System using Python. The simulation models the interactions between the Sun, the planets, and an additional star of the same mass as the Sun. The goal is to investigate the potential disruptions caused by the second star over a span of 100 years.

#### Project Description

We start by setting up a model of our Solar System, including the Sun and planets. For simplicity, all masses are considered point-like, and collisions are neglected. Constants are defined to make quantities dimensionless using cgs units.

#### Masses and Velocities

The masses, initial positions, and velocities of all the bodies in the Solar System are defined. Data is sourced from the NASA Planetary Fact Sheet.
N-Body Equations

The function for the N-body equations is defined to provide the derivatives used for integration.

#### Integration

The equations are integrated over a timespan of 100 years, taking 5000 steps.

#### Visualization

3D positions of the bodies in the Solar System after 100 years are plotted.

![Solar_system](New-solar-system/solar_system.jpeg)

![solar_system](https://github.com/user-attachments/assets/bf2f7348-0db0-4a0f-8f2a-a9f865eade48)

## Adding a Second Star

A second star with the same mass as the Sun is introduced, and its parameters are defined. The new system is integrated over a timespan of 25 years.
New Visualization

The new positions of the bodies in the Solar System, including the second star, are plotted.
