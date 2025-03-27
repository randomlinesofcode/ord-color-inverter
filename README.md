# Invert Colors - Inscriptions

This web tool allows users to retrieve and modify images from Magic Eden's public mirror. Users can load an image by entering an **Inscription ID**, invert its colors, and download the modified image. The tool also enables users to download the original image in its original format.

## Features

- **Load Image**: Retrieve an image from Magic Eden using an **Inscription ID**.
- **Invert Colors**: Invert the colors of the loaded image using a simple button.
- **Download Original or Inverted Image**: Download the image in its original format or the modified (inverted) format.
- **Disclaimer**: The tool does not store or distribute any images; it only retrieves them from the Magic Eden public mirror.

## How to Use

1. **Enter Inscription ID**: Type the Inscription ID in the input field. The Inscription ID should be a 64-character hexadecimal transaction ID followed by "i" and a non-negative integer.
   
   Example:  
   `6fb976ab49dcec017f1e201e84395983204ae1a7c2abf7ced0a85d692e442799i0`
   
2. **Load Image**: After entering the Inscription ID, click on **Load Image** to retrieve the image from Magic Eden.
   
3. **Invert Colors**: Once the image is loaded, click **Invert Colors** to apply the color inversion effect.

4. **Download Image**: After the image is modified (or even without modification), you can click **Download Image** to save the image in the original format (PNG, JPG, etc.).

## Disclaimer

This tool allows you to retrieve and modify images from Magic Eden's public mirror.  
We do not store, distribute, or claim ownership of any images.  
Use this tool at your own discretion.

## Technologies Used

- **HTML**: Structure and content of the web page.
- **CSS**: Styles for the web page layout and design.
- **JavaScript**: Functionality for handling user interactions, loading images, inverting colors, and downloading images.
- **Canvas API**: Used to manipulate and display images directly in the browser.