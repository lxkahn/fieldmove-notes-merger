# Fieldmove note summary code

This repository contains a Python 3 script **fieldmove_notes_merger.py** that merges and sorts the image, plane, note and line .csv files created by the iOS app Fieldmove Clino, discards unnecessary fields, then outputs the result to a presentable LaTeX document that includes thumbnails of the photos.

Requirements:
* Python 3 and standard scientific Python modules

Execution:
* open Terminal
* navigate to the directory in which **fieldmove_notes_merger.py** is saved
  * to do this type `cd [pathname]` in the Terminal prompt where `[pathname]` is the path to the folder
* execute 'python fieldmove_notes_merger.py' in the Terminal prompt
* follow the prompts which will have you enter the following in interactive prompts:
  * the path to the project.fm directory where the .csv and image files are stored
  * the year and field area
  * the name of the folder within the project directory where the images are kept. In order to keep the pdf document generated by LaTeX to a reasonable size, we recommend exporting downsized versions of your imagery into a separate images folder (such as image_thumbnails) keeping the same names for the images.

Outputs:
* **all_notes.csv**
* **all_notes_filtered.csv**
* **latexoutput.tex**

All output files will be created in the same directory in which the Fieldmove .csv’s are stored.
