# ACITE-PROJECT-Stegnography
Image-Based Steganography Tool

🔒 Overview

This is a Streamlit-based web application that allows users to hide secret messages inside images using Least Significant Bit (LSB) steganography combined with AES encryption for added security. It also enables users to retrieve and decrypt hidden messages from encoded images.

🚀 Features

Encrypt messages using AES-256 encryption before embedding them into images.

Hide encrypted messages inside PNG images using LSB steganography.

Extract and decrypt hidden messages using a secure passcode.

Simple web-based interface powered by Streamlit.

Download the encoded image after message embedding.

🛠️ Technologies Used

Python

Streamlit (for the web interface)

OpenCV (for image processing)

NumPy (for numerical operations)

PyCryptodome (for AES encryption)

📦 Installation

Clone the repository:

git clone https://github.com/yourusername/steganography-tool.git
cd steganography-tool

Install dependencies:

pip install -r requirements.txt

▶️ Usage

Run the Streamlit app:

streamlit run app.py

Encoding a Message

Select Encode Message in the UI.

Upload a PNG image.

Enter your secret message.

Provide a passcode to encrypt the message.

Click Encode & Save Image.

Download the encoded image with the hidden message.

Decoding a Message

Select Decode Message in the UI.

Upload the encoded PNG image.

Enter the passcode used for encryption.

Click Decode Message to reveal the hidden message.

⚠️ Limitations

Only supports PNG images.

Message size should be small enough to fit within the image pixels.

Incorrect passcodes will prevent message decryption.
