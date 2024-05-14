# Madrid Public Transport Accessibility Heatmap

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Usage](#usage)
4. [Results](#results)
5. [Madrid Bus Routes](#madrid-bus-routes)
6. [Madrid Metro Lines](#madrid-metro-lines)
8. [License](#license)

## Introduction

This project uses R Markdown to analyze GTFS data from Madrid's public transport system. Given a starting position and time, the available time, and average walking speed, it generates a map of Madrid with an overlaid heatmap. The heatmap displays the travel time to all reachable places within the specified timeframe by walking or taking the bus.

## Features

- **Grid Data Structure**: The project uses a grid data structure to store bus stops, which helps reduce computational cost.
- **Actual Departure Time**: The actual departure time of buses is taken into account when calculating travel times.

## Usage

1. Clone the repository.
2. Run the R Markdown file.
3. Input your starting position, starting time, available time, and average walking speed.
4. The program will generate a heatmap of travel times to all reachable locations.

## Results

Below is an example of the resulting heatmap for starting at 8:15am in Ciudad Universitaria and traveling for 5-10-15-...-60 minutes.

![Acessibility Madrid map](./results/CIU/CIU.gif)

## Madrid Bus Routes

This section provides a map of all Madrid bus routes. The map is generated using the GTFS data from Madrid's public transport system.

![Madrid bus routes map](./results/EMT.png)

## Madrid Metro Lines

This section provides a map of Madrid metro lines. The thickness of the metro line is proportional to the frequency of the line at the specified hour and day. This gives a visual representation of the metro line frequency.

![Madrid metro lines map](./results/metro.png)

## License

**MIT**
