# IPL Player Price Predictor (Frontend) 🏏

A responsive frontend web interface for predicting IPL player auction prices using a machine learning backend.

## Features

- Modern IPL-themed UI
- Fully responsive (mobile, tablet, desktop)
- Smooth animations and clean layout
- Input validation for better user experience
- Dropdown selection for player roles
- Displays prediction result dynamically

## Tech Stack

- HTML
- CSS (Responsive Design)
- JavaScript (Fetch API)

## User Inputs

The interface collects the following details:

- Strike Rate  
- Boundary Percentage  
- Dot Ball Percentage  
- Total Runs  
- Player of Match Count  
- Capped / Uncapped status  
- Playing Role (Batsman, Bowler, All-Rounder, Wicketkeeper)  
- Base Price (in Lakh)

## How It Works

1. User fills in player details.
2. Clicks **Predict Price **.
3. Frontend sends data to backend API.
4. Displays predicted auction price on screen.

## API Integration

The frontend sends a POST request to:

```txt
https://ipl-backend-b28j.onrender.com/predict
