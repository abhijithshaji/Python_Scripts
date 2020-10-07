# Multiscale Template match with OpenCV

1. Code looks for a template in source image
2. Source image is iterated down to all possible scales, so template can match even if dimensions are different.
3. Matched dimensions are cropped from source and then resized to templates dimensions. [crop.jpg]
4. Match is marked in a red rectangle and represented in box.jpg
5. Image to image comparison is done with Image Similarity API
## Execution

Visualized output
```bash
python match.py --template template.png --images source.jpg -v 1
```

Non-Visualized output
```bash
python match.py --template template.png --images source.jpg
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


