# Photoshop

This project is a **Java-based image editor** that allows users to load, edit, and save images using various built-in filters and transformations. It provides a graphical user interface (GUI) built using the Swing library, offering an intuitive and interactive way to manipulate images at the pixel level.

## Features

- **Basic Editing Tools**: 
  - Increase/Decrease Brightness
  - Increase/Decrease Contrast
  - Flip Horizontally/Vertically
  - Rotate Clockwise/Counterclockwise
  - Convert to Black and White
  - Apply Grayscale Filter
- **Custom Filters**: 
  - Invert Colors
  - Gaussian Blur
- **File Operations**: 
  - Load and save images in .jpg format for editing.
  
## How It Works

The program converts images to a 2D array of `Color` objects, enabling pixel-level manipulation for filters and transformations. You can use the menu bar to apply different effects or save the image.

### Menu Options:
- **File**:
  - Load Picture
  - Save Picture
- **Edit**:
  - Increase Brightness
  - Decrease Brightness
  - Increase Contrast
  - Decrease Contrast
  - Flip Horizontally
  - Flip Vertically
  - Rotate Clockwise
  - Rotate Counterclockwise
  - Black and White
  - Gray Scale
- **Bonus**:
  - Invert Colors
  - Gaussian Blur

## How to Run

1. **Prerequisites**:
   - You must have the **Java Development Kit (JDK)** installed on your system.

2. **Compile the Program**:
     ```bash
     javac Harrison_Photoshop.java
3. **Run the Program**:
     ```bash
     java Harrison_Photoshop
