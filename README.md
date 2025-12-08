# Javascript-CNN

Welcome to the **Javascript-CNN** repository! This project is an interactive, in-browser implementation of a Convolutional Neural Network (CNN) using JavaScript and HTML. The goal is to provide a simple, hands-on tool to help you learn, visualize, and experiment with CNN architectures—right in your browser, with no dependencies.

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Getting Started](#getting-started)
- [Vercel Link](#vercel-link)

## About the Project

This project aims to demonstrate the basics of Convolutional Neural Networks (CNNs), the core building block of computer vision and deep learning. This demo is browser-native and implements:
- Convolution + pooling layers
- Fully connected layers
- Simple output layer training (perceptron update, as in the Pascal reference)
- All using modular, readable JavaScript with editable UI

This project is modeled after the [Javascript-MLP](https://github.com/matthewJamesAbbott/Javascript-MLP) tool (multi-layer perceptron)—but for convolutional networks and image-like data!

### Built With
- **HTML**: For the user interface and controls
- **JavaScript**: For CNN logic, training, and visualization

## Features

- Interactive CNN configuration (input size, channels, convolution filters, pooling size, FC layers, output classes)
- Create and modify sample images (random or CSV upload/paste)
- Specify and train on one-hot targets
- See model predictions live after training
- Lightweight and browser-only (no install, runs anywhere)
- Human-readable code for easy education, porting, or extension

## Getting Started

You can use this tool with *any modern web browser*.

### Prerequisites

- Modern web browser (Chrome, Firefox, Edge, Safari, etc.)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/matthewJamesAbbott/Javascript-CNN.git
   ```
2. Open the `index.html` file in your web browser.

That's it! No build step or server required.

## Vercel Link
https://vercel.com/msquigs-projects/javascript-cnn

