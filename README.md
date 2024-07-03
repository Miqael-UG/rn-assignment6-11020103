ID: 11020103

# Mobile Application Development Assignment 6

## Overview

This repository contains the implementation for Assignment 6 of the DCIT202 Mobile Application Development course. The assignment involves creating a mobile application that mimics the provided UI mockup using React Native and AsyncStorage for local data storage.

## Features Implemented

- **HomeScreen**: Displays a list of available products fetched from a mock data source.
- **CheckoutScreen**: Shows selected items added to the cart, with the ability to remove items.
- **Add to Cart Button**: Available on each product item in the HomeScreen for adding items to the cart.
- **Remove from Cart Button**: Allows users to remove selected items from the cart.
- **Local Storage**: Utilizes AsyncStorage from React Native to store selected items locally on the device.

## Screenshots
<img src="https://i.ibb.co/8dQCvfT/Screenshot-20240703-011421.jpg" width="370"/>
<img src="https://i.ibb.co/6wLH82h/Screenshot-20240703-011425.jpg" width="370"/>

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/rn-assignment6-11020103.git
   cd rn-assignment6-11020103
2. **Install Dependencies:**

   ```bash
   npm install
3. **Run the application:**

   ```bash
   npm start

## Implementation Details
 - Data Management: Used React hooks (useState, useEffect) to manage state and AsyncStorage for local data storage.
 - UI Components: Utilized React Native components such as FlatList, Image, Text, and Pressable for building UI elements.
 - Styling: Applied styles using StyleSheet.create() for consistent and responsive UI design across different screens.

