# WATCHYOU-AI

![Screenshot 2024-01-19 230119](https://github.com/Saunakghosh10/watchyou-ai/assets/76943154/ccdb85e1-6540-4a21-b561-3e76c1efb6af)

## Overview

This project is a web application that leverages machine learning and deep learning algorithms for real-time object detection using the COCO-SSD model from TensorFlow.js. The application allows users to interact with their webcam, capture snapshots, record videos, and toggle various settings.

## Features

- **WATCHYOU-AI:** Utilizes COCO-SSD to detect objects in the webcam feed.
- **Auto Record:** Automatically starts recording when a person is detected in the video feed.
- **User Interaction:** Buttons for flipping the video horizontally, taking screenshots, and manual video recording.
- **Settings:** Volume control for notifications and a dark mode toggle.
- **Intuitive UI:** Designed with a user-friendly interface for easy interaction.

## Prerequisites

- Node.js: [Download and install Node.js](https://nodejs.org/)

## Installation

1. Clone the repository: `git clone https://github.com/Saunakghosh10/watchyou-ai.git`
2. Navigate to the project directory: `cd watchyou-ai`
3. Install dependencies: `npm install`

## Usage

1. Start the development server: `npm run dev`
2. Open your web browser and visit `http://localhost:3000`

## Configuration

- Adjust settings in the `src/components/theme-toggle` and other relevant files to customize the application behavior.

## Dependencies

- React
- TensorFlow.js
- COCO-SSD
- Lucide-react
- React-loader-spinner
- Sonner
- React-webcam

## Contributing

Contributions are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md).

## Acknowledgments

- Special thanks to the creators of TensorFlow.js and COCO-SSD for their powerful tools.

