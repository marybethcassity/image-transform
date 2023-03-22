# image-transform
resize images while maintaining image center and aspect ratio, also transforms corresponding coco annotations

## Usage 
update the original image path, the cropped image path, and the resized (final) image path. Alternatively, the code can be edited to crop the image after resizing without saving the image in between these steps.

update the coco annotations file path 

update the transformed annotations file path in the variable result_file

only run the the second cell if you are unsure of the smallest image dimension 

only run the third cell if you are sure of the smallest image dimension and have updated this variable, otherwise comment this cell out
