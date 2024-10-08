  Synthetic Data Generator (SDG) - README

Synthetic Data Generator (SDG)
==============================

The **Synthetic Data Generator** is a powerful Unity-based tool designed to generate high-quality, diverse datasets for machine learning models, particularly focused on one-shot and few-shot learning tasks. Leveraging Unity's robust rendering engine and advanced randomization techniques, this tool enables the creation of realistic and scalable image datasets for various applications such as autonomous driving, healthcare, and robotics.

Access the App
--------------

[arithescientist.com/sdg](https://arithescientist.com/sdg)

Table of Contents
-----------------

*   [Overview](#overview)
*   [Features](#features)
*   [Installation](#installation)
*   [Usage](#usage)
*   [System Requirements](#system-requirements)
*   [Contribution](#contribution)
*   [License](#license)

Overview
--------

The **Synthetic Data Generator** allows users to create diverse datasets with customizable parameters, including lighting, object textures, camera angles, and surface roughness. Designed to be scalable, the app supports parallel processing for fast dataset generation and is deployable on both local systems and cloud platforms.

### White Paper

For detailed insights, read the white paper: **[Synthetic Data Generation for One-shot/Few-shot Image Synthesis: A Comprehensive Approach](https://arithescientist.com/sdg-whitepaper)**

Features
--------

*   **Randomization of Image Features**: Includes surface roughness, lighting, camera angles, and object movement to mimic real-world variability.
*   **Cross-Platform Support**: Deployable on Mac, Windows, and Linux, ensuring accessibility to a wide range of users.
*   **Scalable Architecture**: Supports parallel processing to handle large datasets efficiently.
*   **Custom Texturing**: Allows user-uploaded images to be applied to segmented parts of objects.
*   **Realism and Flexibility**: Simulates diverse scenarios using Unity s physics-based rendering.
*   **Cloud Deployment**: Future support for AWS EC2 for large-scale data generation.

Installation
------------

### Prerequisites

*   **Unity 3D** (tested with version 2021.1 or higher)
*   Compatible operating system: Windows, macOS, or Linux

### Steps

1.  Clone the repository:
    
        git clone https://github.com/arithescientisttt/synthetic_data_generator.git
    
2.  Open the project in Unity:
    *   Launch Unity Hub.
    *   Open the **Synthetic Data Generator** project folder.
3.  Install any required Unity packages through the Package Manager.
4.  Build the project:
    *   Select your target platform (Windows, macOS, or Linux).
    *   Click on **Build** to compile the application.

Usage
-----

1.  **Run the App**:
    *   On first-time setup, the app will create a default folder on the user's desktop called **SDG Capture Data** where all generated datasets are stored.
2.  **Configure Parameters**:
    *   You can adjust lighting, object movement, camera angles, and texture mapping via the app's UI.
    *   Optionally, upload custom textures to apply to specific sections of objects.
3.  **Start Data Generation**:
    *   Use the app to generate datasets based on your configured settings.
    *   Images will be saved automatically in the desktop folder or a custom folder if specified.
4.  **Access Output**:
    *   All generated images and metadata will be available in the **PerceptionCaptureData** folder on your desktop.

System Requirements
-------------------

*   **Operating Systems**: Windows 10+, macOS, Linux
*   **Hardware**: A system with at least 8GB RAM and a GPU that supports Unity rendering for optimal performance.
*   **Unity Version**: 2021.1 or higher

Contribution
------------

We welcome contributions to improve the **Synthetic Data Generator**. Feel free to submit issues, pull requests, or feature suggestions through our GitHub repository.

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature-branch`).
3.  Make your changes.
4.  Submit a pull request for review.

License
-------

This project is licensed under the **MIT License**. For more information, see the [LICENSE](LICENSE) file in the repository.

For more details, check the [white paper](https://www.arithescientist.com/post/synthetic-data-generation-for-one-shot-few-shot-image-synthesis-a-comprehensive-approach).