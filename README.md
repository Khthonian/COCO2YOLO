# COCO2YOLO

This is a customised Jupyter Notebook script to manage the conversion of a COCO dataset format into a YOLO format.

## Requirements

The script does not have many requirements, but they are included in a `requirements.txt` file; the script will install them automatically.

## Annotations

The repository comes with sample COCO datasets in the `annotations` directory, and this is where I would recommend storing any additional datasets.

## Usage

To use the script, simply go to the bottom of the notebook file and input the following:

- The path to the COCO dataset, preferably in annotations.
- The desired output path for the YOLO dataset; this will be created if it does not exist, and will be overwritten otherwise.
- The maximum number of classes allowed by the model; this is typically 13 for the RGB datasets and 15 for the thermal datasets.
