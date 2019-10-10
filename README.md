# Keras_darknet
Weight format conversion between Keras and Darknet.

# Prepage Running Environment
```
$ conda create -n keras_darknet python=3.6 pip
$ conda activate keras_darknet
$ pip install -r requirements.txt
```

# Weight Conversions
```
# to convert keras to darknet format
$ python keras_to_darknet.py -cfg_path <your darknet cfg file path> -weights_path <input keras weight path> -output_path <output darknet weight path>

# to convert darknet to keras format
$ python darknet_to_keras.py -cfg_path <your darknet cfg file path> -weights_path <input darknet weight path> -output_path <output keras weight path>
```

# Reference
- https://github.com/chineseocr/chineseocr/tree/app/tools
