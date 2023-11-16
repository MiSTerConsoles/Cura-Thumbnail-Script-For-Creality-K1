# Cura-Thumbnail-Script-For-Creality-K1
This is a post-processing script to get thumbnail images on the Creality K1/K1 Max machines. It is a modified version of the original CreateThumbnail.py script. In order to use it place the file in the "scripts" folder. Then in Cura you will go to Extensions --> Post Processing --> Modify G-Code. Select the CreateThumbnailK1.py script and set width/height to 96 pixels.

![96px](https://github.com/MiSTerConsoles/Cura-Thumbnail-Script-For-Creality-K1/assets/80081591/43c7ee67-c5fb-4c9a-a32e-e6c7c007e7f8)

Create another instance of the script and set width/height to 300 pixels.

![300px](https://github.com/MiSTerConsoles/Cura-Thumbnail-Script-For-Creality-K1/assets/80081591/f6483e75-2e0f-4474-8c6a-3b1dfb9668bb)

If you also want a preview thumbnail of your STL file on your PC you will need to add the original [CreateThumbnail.py](https://github.com/Ultimaker/Cura/blob/main/plugins/PostProcessingPlugin/scripts/CreateThumbnail.py) script to Cura. Select that as well and set width/height to 300 pixels.

![300px PC](https://github.com/MiSTerConsoles/Cura-Thumbnail-Script-For-Creality-K1/assets/80081591/126af770-5c38-499a-9f72-0d4f72c9c733)

Once you have those scripts set up your object should have thumbnails on the K1 display as well as on your PC and in Fluidd/Mainsail. All credit goes to the author of the original script that I tweaked. Happy printing!
