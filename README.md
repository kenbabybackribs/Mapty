# Fitness Tracking App

## Overview

The Fitness Tracking App is a web application designed to help users track their running and cycling workouts on a map. It leverages Mapbox for interactive map features and Google Maps Street View for location images. Users can log their workouts, view their activities on the map, and visualize their routes with detailed metrics.

## Features

- **Interactive Map**: View your location and track workouts on an interactive map using Mapbox.
- **Workout Logging**: Log running and cycling workouts with metrics such as distance, duration, cadence (for running), and elevation gain (for cycling).
- **Location Visualization**: Reverse geocode the workout location to display detailed location information and street view images.
- **Error Handling**: Handles geolocation and API errors gracefully.
- **Local Storage**: Save and retrieve workout data using local storage.
- **Route Visualization**: Display routes on the map based on workout data.

## Demo

Check out a demonstration of the app in action:

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/989320848?autoplay=1&loop=1" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div>

## Live Site

Explore the live application here: [Fitness Tracking App](https://mapty-v02.netlify.app/)

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- A Mapbox account for map functionality. Obtain an access token from [Mapbox](https://www.mapbox.com/).
- A Google Maps API key for street view images. Obtain an API key from [Google Cloud](https://cloud.google.com/maps-platform).

### Installation

1. **Clone the Repository**

   ```bash
   git clone <repository-url>
   cd <repository-directory>
