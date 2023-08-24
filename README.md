# Remove Background Using Python

Python code to remove background from an image

This is a simple Python project that demonstrates how to remove the background from an image using the `rembg` library and manipulate images using the `PIL` (Pillow) library. The project is created in a Jupyter Notebook using Google Colaboratory.

## Installation

To use the background removal functionality, you need to install the `removebg` library. You can install it using the following command:

```Python
pip install rembg
```

You also need to have the `PIL` library installed. If you don't have it already, you can install it with:

```Python
pip install PIL
```

## Usage

1. Make sure you have both the `rembg` and `PIL` libraries installed.
2. Open the Jupyter Notebook (`RemoveBackground.ipynb`) using Google Colaboratory or Anaconda.
3. Manually provide an image by uploading it to the Colaboratory notebook or store the image in the same folder as the notebook.
4. Locate the section of the notebook where an image path is specified and replace it with the path to your image.

 ```Python
 # Path to your input image
 input_path = "your_image.jpg"
 ```
   
5. Run the code cells in the notebook.
6. After running the code, a PNG file will be generated in the same folder with the background removed.

### Before

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/AartiDashore/RemoveBackground/blob/main/Morticia.jpg">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/AartiDashore/RemoveBackground/blob/main/Morticia.jpg">
  <img alt="Shows Morticia in dark mode." src="https://github.com/AartiDashore/RemoveBackground/blob/main/Morticia.jpg">
</picture>

### After

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/AartiDashore/RemoveBackground/blob/main/output.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/AartiDashore/RemoveBackground/blob/main/output.png">
  <img alt="Shows Morticia in dark mode." src="https://github.com/AartiDashore/RemoveBackground/blob/main/output.png">
</picture>


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to use this project for your background removal tasks! If you encounter any issues or have suggestions, please feel free to open an issue or contribute to the project.

---
