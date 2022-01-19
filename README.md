# qupath-project-fixer
 
Simple program that makes it possible to directly run other people's qupath projects, without the need to re-importing all images again.

To use the software:
1) **Download the executable located in Releases** (click [here](https://github.com/andreped/qupath-project-fixer/releases/tag/v0.1.0) to access the software)
2) Run the downloaded executable (which should open a file explorer)
3) From the file explorer, select the project file to be fixed
4) From the new file explorer, select the directory containing the corresponding .vsi-files

NOTE: that this is only designed to work for CellSens VSI (.vsi). It also only updates the names in the project file such that they match what was used in the QuPath-0.1.2 version. Hence, it might not work for all versions. It is also assumed that all WSIs relevant for the project are located at the same level (in the same directory). As for now, since it's an executable, it only works for Windows.
