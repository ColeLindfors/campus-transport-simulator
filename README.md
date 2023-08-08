# Campus Transport Simulator

**Note: The source code for this project is not available due to school regulations.**

## Introduction

Welcome to the Campus Transport Simulator - a project that brings together robots and vehicles to revolutionize campus transportation. This simulation offers an insight into a world where algorithms and vehicles collaborate to enhance your mobility experience.

## Simulation Overview

The Campus Transport Simulator presents two key components that provide a comprehensive understanding of its capabilities.

### The Scheduler: Crafting Journeys

The scheduler empowers users to design customized journeys. Users can name their robot, select a vehicle, and choose a pathing algorithm. Multiple algorithms cater to drones and cars, optimizing routes across the campus. After inputting the start and end points, a personalized trip can be scheduled.

### The Visual Representation: Real-time Observation

The simulation visually renders scheduled trips on a three-dimensional model of the University of Minnesota campus. Real-time tracking allows users to observe their journeys in action, with adjustable speeds for varying levels of engagement.

## Running the Simulation

Effortlessly initiate the simulation by following the instructions below:

### Docker Deployment

1. Install Docker Desktop (download link [here](https://www.docker.com/products/docker-desktop/)).
2. Pull the Docker image using this command:
    ```bash
    docker pull colelindfors/campus-transport-simulator
    ```
3. Start the simulation:
    ```bash
    docker run -it --rm -p 8081:8081 colelindfors/campus-transport-simulator
    ```
4. Access the simulation at:
    - http://127.0.0.1:8081/ for the simulation interface
    - http://127.0.0.1:8081/schedule.html for the scheduler

## Project Background

The Campus Transport Simulator embodies the collaboration and skill of a group of software developers. Over two months, this project integrated design patterns, Google code styling, and meticulous documentation to create a seamless user experience.

## Introducing New Features

### Diversifying Mobility

A recent update introduces several new features, most notably the inclusion of multiple pickup vehicles. This enhancement expands beyond the solitary drone, encompassing a variety of vehicles with distinct search algorithms and transport behaviors.

#### A Variety of Choices

The once-singular drone has been joined by a fleet of vehicles, each boasting unique attributes. The drone maintains its swift and direct approach, while the hovering car navigates roads and the helicopter adds an aerial perspective to pickups.

### Practical Impact

The inclusion of multiple vehicles adds versatility to the simulation. Users benefit from a range of choices, injecting variety into the experience. This diversity also translates into increased efficiency, as multiple vehicles can now operate simultaneously, maximizing the number of completed trips.

### Integrating New Features

To smoothly integrate these enhancements, we employed additional design patterns. The strategy behavioral design pattern facilitated customized pathing strategies for each vehicle. Additionally, a facade structural design pattern simplified user interactions with the new pickup vehicle selector.
