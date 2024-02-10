# VirtualReality-For-Education

## Overview

The VirtualReality-for-Education project aims to create an interactive virtual classroom environment using Unity. The project utilizes AI technology to simulate a virtual teacher that can provide educational content and interact with students.

### AI Integration

The project integrates with the Gemini API from Google's GenerativeAI to generate responses for virtual teacher interactions. The AI responds to prompts provided by the user, simulating a conversation between the virtual teacher and the student.

## Unity Project Setup

### Prerequisites

- Unity Hub installed on your system.
- Unity version 2022.3.19f1 installed.

### Steps

1. Download and install [Unity Hub](https://unity.com/download) from the official Unity website.
2. Launch Unity Hub and sign in with your Unity ID.
3. In Unity Hub, go to the Installs tab and click "Add" to add the Unity version 2022.3.19f1.
4. Once installed, create a new Unity project and select the Unity version 2022.3.19f1.
5. Clone or download the VirtualReality-for-Education project repository from GitHub.
6. Open the Unity project in Unity Editor.

## Adding Classroom Prefab

1. In the Unity Editor, navigate to the "Prefabs" folder in the project.
2. Locate the "Classroom" prefab.
3. Drag and drop the "Classroom" prefab into the scene hierarchy to add it to your scene.

## Attaching C# Script

1. Locate the "AIRequestUI.cs" script in the project assets.
2. Drag and drop the "AIRequestUI.cs" script onto any GameObject in the scene. This script handles user interactions and communicates with the AI server.

## Running Flask Server for Gemini API

1. Make sure you have Python installed on your system.
2. Install Flask using pip:

    ```
    pip install Flask
    ```

3. Navigate to the directory containing the "app.py" file in the Virtual Teacher project.
4. Run the Flask server by executing the following command:

    ```
    python app.py
    ```

5. The Flask server should now be running, and the Unity project can communicate with the Gemini API for AI responses.

## Unity Package Dependencies

### XR Interaction Toolkit

1. In the Unity Editor, go to Window > Package Manager.
2. Select the XR Interaction Toolkit from the list of available packages.
3. Click "Install" to install the XR Interaction Toolkit package.
4. Additionally, import the Starter and XR Device Simulator assets from the XR Interaction Toolkit for development and testing.
5. Also add all the necessary input actoins required for moving around the scene in editor mode.

### Classroom Asset

Download the "School Assets" package from the Unity Asset Store using the following link: [School Assets - Unity Asset Store](https://assetstore.unity.com/packages/3d/environments/school-assets-146253)

