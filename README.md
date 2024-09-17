# RootTracer: An Intuitive Solution for Root Image Annotation

RootTracer is a tool designed for efficient plant root image analysis, allowing users to annotate, modify, and extract RSML files. 
The tool addresses challenges such as complex root structures, occlusions, and inconsistent lighting. 
RootTracer enables manual annotations, modification of existing RSML files, and extraction of root traits like length, convex hull area, and tortuosity. 
It supports various plant species and integrates intuitive controls for enhanced user experience.
A new dataset for training machine learning models in root segmentation is also introduced, facilitating advancements in root phenotyping and agricultural research.

Dataset available [here](#).

**Authors:** Maichol Dadi, Alessandra Lumini, Annalisa Franco, Giuseppe Sangiorgi, Silvio Salvi


## Getting Started

### Requirements:
- No external dependencies are required.
- Compatible with any system that supports RSML files.
- High-resolution images of plant root systems (e.g., .png, .jpg).


## Usage Guide

### Loading an Image:
- Open the tool and load the image file containing the plant roots you wish to analyze.
- **Supported formats:** `.png` and `.jpg`.

### Creating Annotations:
- Use the **'Add Plant'** button to create a new plant entry.
- Use the **'Add Root'** button to manually trace root systems by clicking key points along the root structure.

### Editing RSML Files:
- RootTracer allows you to load existing RSML files from other tools for further modification.
- Adjust root structures by dragging or modifying key points, such as tips, segments, or root origins.

### Extracting Measurements:
- RootTracer can automatically calculate and extract key measurements, such as total length, convex hull area, and tortuosity.
- The results are saved directly within the RSML file and can be exported in CSV format.

### Saving and Exporting:
- Save your annotations and measurements as an RSML file.
- Export the data in CSV format for further analysis.

### Mask Visualization:
- RootTracer provides an option to visualize an overlay mask of the annotated roots on top of the original image, helping validate your work.

## Additional Features:
- **Automated CSV extraction:** Quickly extract and compile measurements from all RSML files in a directory.
- **Root selection:** Choose specific roots, including primary and secondary roots, for detailed analysis.

## Support:
For questions or issues, please open a GitHub issue or contact the authors directly (maichol.dadi2@unibo.it).


