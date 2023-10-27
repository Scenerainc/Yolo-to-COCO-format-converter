# Yolo-to-COCO-format-converter
### Simple Directions for Use
I forked this repository (https://github.com/Taeyoung96/Yolo-to-COCO-format-converter) and modified some parts of the code to make it suitable for our purposes.

Before running the `main.py` script, you need to change the `FILE_URL`, which specifies the directory path that includes the training image data. Additionally, you should define all the classes that the dataset contains in the `classes` list.

To run the conversion script, use the following command:
- `python main.py --path <Absolute path to dataset_root_dir> --output <Name of the json file>`

The dataset directory should have the following structure:
<pre>
    dataset_root_dir/
        Photo_00001.jpg
        Photo_00001.txt
        Photo_00002.jpg
        Photo_00003.txt
</pre>

After the conversion process is complete, you can check the converted file in the `output` directory.