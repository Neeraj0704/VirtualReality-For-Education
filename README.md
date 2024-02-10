Virtual Teacher - Unity Project
Overview
The Virtual Teacher project aims to create an interactive virtual classroom environment using Unity. The project utilizes AI technology to simulate a virtual teacher that can provide educational content and interact with students.

AI Integration
The project integrates with the Gemini API from Google's GenerativeAI to generate responses for virtual teacher interactions. The AI responds to prompts provided by the user, simulating a conversation between the virtual teacher and the student.

Unity Project Setup
Prerequisites
Unity Hub installed on your system.
Unity version 2022.3.19f1 installed.
Steps
Download and install Unity Hub from the official Unity website.
Launch Unity Hub and sign in with your Unity ID.
In Unity Hub, go to the Installs tab and click "Add" to add the Unity version 2022.3.19f1.
Once installed, create a new Unity project and select the Unity version 2022.3.19f1.
Clone or download the Virtual Teacher project repository from GitHub.
Open the Unity project in Unity Editor.
Adding Classroom Prefab
In the Unity Editor, navigate to the "Prefabs" folder in the project.
Locate the "Classroom" prefab.
Drag and drop the "Classroom" prefab into the scene hierarchy to add it to your scene.
Attaching C# Script
Locate the "AIRequestUI.cs" script in the project assets.
Drag and drop the "AIRequestUI.cs" script onto any GameObject in the scene. This script handles user interactions and communicates with the AI server.
Running Flask Server for Gemini API
Make sure you have Python installed on your system.
Install Flask using pip:
bash
Copy code
pip install Flask
Navigate to the directory containing the "app.py" file in the Virtual Teacher project.
Run the Flask server by executing the following command:
bash
Copy code
python app.py
The Flask server should now be running, and the Unity project can communicate with the Gemini API for AI responses.
Unity Package Dependencies
XR Interaction Toolkit
In the Unity Editor, go to Window > Package Manager.
Select the XR Interaction Toolkit from the list of available packages.
Click "Install" to install the XR Interaction Toolkit package.
Additionally, import the Starter and XR Device Simulator assets from the XR Interaction Toolkit for development and testing.
