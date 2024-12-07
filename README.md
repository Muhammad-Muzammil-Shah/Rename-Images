
# Image Renamer Script

This Python script renames image files in a specified directory with sequential numbers (e.g., `1.jpg`, `2.png`, etc.). It's useful for organizing images with consistent naming.

## Features
- Automatically detects and renames image files in a folder.
- Sequentially numbers image files based on their original order.
- Supports common image formats (e.g., `.jpg`, `.png`).

## Prerequisites
- Python 3.x installed on your system.
- Basic knowledge of running Python scripts.

## Installation
1. Clone or download the repository.
2. Ensure the required Python version is installed.

## Usage
1. Place the script in the same folder as your images or provide the folder path in the code.
2. Open the script and update the `folder_path` variable with your directory's path.
3. Run the script:

   ```bash
   python rename_images.py
   ```

4. The images will be renamed to `1.ext`, `2.ext`, etc., where `.ext` is the original file extension.

## Example
Before running the script:
```
image1.jpg
photo2.png
random.jpg
```

After running the script:
```
1.jpg
2.png
3.jpg
```

## Notes
- Make a backup of your images before running the script.
- The renaming order depends on the alphabetical order of filenames in the directory.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributions
Feel free to fork the repository, create pull requests, or report issues.

## Acknowledgments
- Inspired by the need for consistent image naming in projects.
```

Save this as `README.md` in the same directory as your script. Let me know if you need further adjustments!
