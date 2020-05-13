# py-rdf
## A python rewrite of the UBFunkeysRDF utility
### Created by Jake Saunders

The file convert.py can be used to convert befween .rdf (Radica Data Files) used in the game UB Funkeys and .xml files for easy editing.

The code used to translate between rdf (Radica Data Files) and xml is based off Daleth and Vincentetcarine's Java UBFunkeysRDF utility [which can be found here](https://github.com/WeNeedCoffee/UBFunkeysRDF).

### Requirements
Python 3.x
### Usage
Open cmd (or your operating system's equivalent). Navigate to the py-rdf directory and type `python convert.py PATH`, where PATH is the path of the .rdf/.xml file to be converted.

PATH can be relative or absolute. The converted file will have the same name but with a different extension and will be placed in the same location as the original file. The original file will be retained. 

Note if a file with the name intended for the converted file already exists at FILE_PATH, it will be overwritten with the new converted file. With this in mind, ensure you backup any profile.rdf files so as to not lose your saves.