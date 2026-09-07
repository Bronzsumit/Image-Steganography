# Steganography

A simple Python GUI application that allows you to **hide secret text inside an image** and later reveal the hidden message.

The application is built using **Tkinter** and the `stegano` library.

## Requirements

* Python 3.x
* `Pillow`
* `stegano`
* Tkinter

## Installation

Install the required modules:

```bash
pip install pillow stegano
```

Tkinter is usually included with Python.

## Run

Run the Python file:

```bash
python steganography.py
```

## Features

* Open an image
* Hide text inside an image
* Save the encoded image
* Reveal hidden text from an encoded image
* Clear the image and text
* Simple graphical user interface

## How It Works

1. Click **Open Image** and select an image.
2. Enter your secret message in the text box.
3. Click **Hide Data** to encode the message into the image.
4. Click **Save Image** to save the encoded image.
5. To reveal a hidden message, open the encoded image and click **Show Data**.

The project uses **LSB (Least Significant Bit) steganography** through the `stegano` library to hide the message inside the image.

## Supported Image Formats

* PNG
* JPG/JPEG

> **Note:** PNG is recommended when saving an image containing hidden data because JPEG compression can affect hidden information.


