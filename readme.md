### xml and javascript project
# Weather and News Application

## Project Overview

This project consists of a **Weather Application** (Karol-Weather) and a **News** page, which fetch real-time data from external APIs to provide users with live weather updates, a weather map, and the latest news from various categories. It also includes a **Contact Us** page where users can submit their details, which are stored in JSON format using **Node.js** and **Express** on the backend.

## Features

### **Karol-Weather Application**
- Fetches **real-time weather data** for the **current location** and allows users to **search for a city**.
- Displays **current weather conditions** as temperature.
- Weather icons visually represent the current weather conditions (e.g., sunny, cloudy, rainy).
- Displays the **current date and time** alongside the temperature.
- Provides a **5-day weather forecast**   with dynamic weather icons.
- Features a **world weather map** that shows **temperature, pressure, precipitation**, and **cloud coverage** using **Leaflet.js**.
- A **Contact Us page** allows users to submit their details, which are stored in **JSON format** using **Node.js** and **Express**.

### **Ponnu-News Page**
- Fetches **news** from multiple categories: **General**, **Entertainment**, **Health**, **Science**, **Sports**, and **Technology**.
- Users can select a category, and the app fetches and displays **news articles** from that category.
- Articles include title, description, image, and a "Read More" link to the full article.
- API requests are dynamically constructed using a country code, selected category, and API key.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, Leaflet.js
- **Backend**: Node.js, Express
- **APIs**:
  - **OpenWeatherMap API** for weather data
  - **NewsAPI** for fetching news articles

## Setup and Installation

### Prerequisites

1. **Node.js** and **npm** should be installed on your local machine.
2. Obtain an **API Key** from OpenWeatherMap (for weather data) and NewsAPI (for news data).

### Steps to Run Locally

1. naviagte to project folder
2. 	Install Dependencies (if any libraries or APIs require it):
    npm install
    cd contactserver
    npm init -y
    npm install express cors
    In terminal navigate to contactserver folder and run node server.js. Server is  now running at http://localhost:3000 .


### deployment link:
https://karolsabu.github.io/

We deployed  this site using githubpages.