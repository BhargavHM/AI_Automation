AI Food Image Processing Pipeline

This project automates the process of collecting and preparing food images from a restaurant menu Excel file.

Context

The input Excel file contains 420 food records. The pipeline reads the food names, searches for suitable images, downloads image candidates, checks their sharpness, and processes the selected images into a standard format.

For the current run, 250 images were processed and validated successfully. The remaining food records were not processed because the testing was limited to 250 images.

Contents
raw_images/

Contains the original images downloaded during the search process.

processed_images/

Contains the final food images after resizing, cropping, and compression.
250 processed images are included.

reports/

Contains two Excel reports:

final_image_quality_report.xlsx — quality details for the 250 processed images, including dimensions, file size, sharpness score, and validation status.
company_image_processing_report.xlsx — maps the food names from the Excel file to their corresponding images and processing status.

processing_report.xlsx is not included because it was an intermediate report generated during the processing.

Current result
420 food records
258 unique food names
250 processed images
412 records matched with images
8 records without images

The project currently covers the local image collection and processing stage. Google Drive upload has not been added yet.
