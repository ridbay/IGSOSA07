# IGSOSA Member Birthday Flyer Generator

A simple, interactive web tool designed to generate personalized birthday flyers for IGSOSA (Ibadan Grammar School Old Students' Association) members.

## Features

- **Interactive Customization**: Easily input the celebrant's name and upload their photo.
- **Dynamic Theming**:
  - **Name-Based Themes**: The color scheme automatically updates deterministically based on the celebrant's name, ensuring a unique yet consistent look for everyone.
  - **20+ Premium Themes**: A wide variety of professionally curated color palettes (Violet & Gold, Teal & Amber, Rose & Pink, etc.).
  - **Randomization**: Don't like the auto-selected theme? Use the "Change Colors" button to cycle through other options manually.
- **Smart Message Generation**: Automatically selects one of 20+ warm, celebratory birthday wishes.
- **Validation**: Download button remains disabled until a valid name is entered to prevent incomplete flyers.
- **High-Quality Export**: Generates and downloads a high-resolution PNG image (2x scale) of the flyer using `html2canvas`.

## How to Use

1.  **Open the Application**: Simply double-click `index.html` to open it in your web browser. No server installation is required.
2.  **Enter Details**:
    - Type the **Celebrant's Name** in the text field. Watch the theme change instantly!
    - Click "Choose File" to **Upload a Picture** of the celebrant.
3.  **Customize (Optional)**: If you prefer a different color scheme, click the **"Change Colors"** button until you find one you like.
4.  **Download**: Click the **"Download Flyer"** button to save the image to your device.

## Tech Stack

- **HTML5**: Semantic structure.
- **Tailwind CSS (via CDN)**: Utility-first styling for rapid UI development and easy theming.
- **JavaScript (Vanilla)**: Logic for interactions, dynamic CSS variable updates, and theme generation.
- **html2canvas**: Library for rendering the DOM to a canvas for image generation.
