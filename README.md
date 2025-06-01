# Carbon Footprint Analyser

## Overview

This Full Stack web application enables users to estimate their carbon footprint by analyzing emissions across multiple categories. Built with the MERN stack, it offers a seamless experience for inputting data and visualizing the results through dynamic charts. Additionally, the dashboard section showcases recent updates and activities related to environmental research and initiatives.

## Key Features

### Carbon Footprint Calculator

- **Detailed Emission Categories**  
  Users can provide data for three main emission scopes:
  - **Scope 1:** Direct emissions from fossil fuel usage and fugitive sources (e.g., methane leaks).
  - **Scope 2:** Indirect emissions associated with electricity consumption.
  - **Scope 3:** Indirect emissions from water usage and waste generation.

- **Comprehensive Calculation**  
  The tool aggregates emissions across all scopes to present a total carbon footprint estimate.

- **Visual Data Representation**  
  Emission data is presented through interactive charts, making it easy to understand emission distribution and identify key contributors.

### Dashboard

- **Activity Feed**  
  Displays updated information on various environmental projects, publications, seminars, and related events.

- **Admin Controls**  
  Authorized users can upload new data and download existing records in Excel format, ensuring that the dashboard remains current and informative.

## Technology Stack

- **React.js:** Frontend user interface.
- **ExcelJS:** Processes Excel files to extract emission data for calculations.
- **Chart.js:** Generates interactive charts for visualizing carbon footprints.
- **MongoDB:** Database management for storing dashboard content.
- **Node.js & Express:** Backend server handling API requests and database interactions.

## Setup Instructions

To run the application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
2. Navigate into each relevant directory (calculator, dashboard, backend) and install dependencies:
    ```bash
    npm install
3. Start the frontend server (calculator or dashboard):
    ```bash
    npm start
4. Move to the backend directory and launch the server:
    ```bash
    cd backend
    node server.js
