# Barcode Scanner with Number Entry
Created by: Walter Pan
Date:4/24/2023
Version: 1.0

This is a barcode scanner application that allows users to scan barcodes and enter a number using a graphical user interface (GUI). The application then saves the scanned barcode data, timestamp, and the entered number to a text file.

## Features

- Real-time barcode scanning
- Decoding barcodes using the Pyzbar library
- Incrementer dialog for entering numbers with increment and decrement buttons
- Manual number entry option
- Error checking for invalid and non-matching number inputs
- Saving barcode data, timestamp, and the entered number to a text file


## How it works

1. The application captures video frames from the camera using OpenCV.
2. The captured frames are decoded using the Pyzbar library to extract barcode data.
3. When a barcode is detected, a custom dialog with a button number incrementer is displayed. Users can increment or decrement the number using the buttons or enter the number manually.
4. If the entered number is invalid or does not match the number from the incrementer, the user is prompted to try again.
5. Once a valid number is entered, the application saves the barcode data, timestamp, and the entered number to a text file named `barcode_data.txt`.
6. The process repeats until the user presses 'q' to exit the application.

## Usage

To use the application, simply run Inventory Tracker Scanner v1.0.exe.

When the application starts, point the camera at a barcode to scan. A dialog will appear, allowing you to enter a number using the incrementer buttons or manual entry. Once you've entered a valid number, the application will save the barcode data, timestamp, and entered number to the `barcode_data.txt` file. To exit the application, press 'q'.
