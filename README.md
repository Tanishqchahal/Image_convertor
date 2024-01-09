# Image_convertor
 Using python's pil library and other functions on nested lists to create different image effects like mirror, greyscale, invert, compress and merge two images.

# How to execute

* To use the mirror, greyscale, invert and compress functions use the following format:   
    * `print(image_from_raw(function_name(get_raw_image("image_name.jpg"))),"converted_image_name.jpg")`   
* for example:   
    * `print(image_from_raw(mirror(get_raw_image("tree.jpg"))),"mirror_tree.jpg")`
* To use the merge function use this format:
   *  `print(image_from_raw(merge(get_raw_image("tree.jpg"),get_raw_image("fruit.jpg")),"merge_tree.jpg")`
