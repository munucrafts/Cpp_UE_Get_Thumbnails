# Cpp_UE_Get_Thumbnails Plugin

## Description
- The Cpp_UE_Get_Thumbnails plugin is designed for Unreal Engine 5.2 and above. It enables users to save thumbnails of assets in the content browser to .png files by automatically creating a folder named "Thumbnails" in the project directory.

  ![Plugin - Save Asset Thumbnails UE](https://github.com/munucrafts/Cpp_UE_Get_Thumbnails/assets/66869650/47c77d93-03da-4358-a25d-5ad3de8c67ba)

## Installation
- Install the rembg module using the command "pip install rembg" in CMD. The rembg module will help us to remove the background of the images.
- Download this https://github.com/danielgatis/rembg/releases/download/v0.0.0/u2net.onnx and copy to "C:\Users\YOUR NAME HERE\.u2net". The rembg module uses this one.
- Download the GitHub repository.
- Extract the contents of the zip file into the Plugins folder of your Unreal Engine project.
- Launch Unreal Engine and enable the plugin from the Plugins menu.
- Tutorial Video : https://youtu.be/zjpgdz6cLsc

## How to Use?
- Select the assets for which you want to save thumbnails.
- Right-click on the selected assets and choose the "SaveThumbnailsFromAssets" option from the "Scripted Asset Actions".
- Thumbnails will be saved as .png files in the "Thumbnails" folder located in your project directory.
  
## License
- Feel free to use or modify this plugin according to your requirements. Attribution is appreciated but not required. If you use this plugin in your project, please consider mentioning the author in your project credits or README file.
