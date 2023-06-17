Sure! Here's the generated `readme.md` file for your GitHub documentation:

```markdown
# Google Photos Metadata Export Solution

This solution is designed to add metadata to multimedia files exported from Google Photos using Google Takeout. When you export all your multimedia files from Google Photos, the metadata is stored in JSON files, making it difficult to export them to another cloud service or organize them in a photo management platform.

## Table of Contents

- [Description](#description)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

The Google Photos Metadata Export Solution provides a set of Python scripts that automate the process of organizing multimedia files and adding metadata to them. The scripts perform the following tasks:

- Collect JSON data: Creates a Pandas DataFrame from JSON data stored in multiple files within a specific folder.
- Files mapping: Generates a file mapping DataFrame for files in the current script directory and its subdirectories.
- Modify JSON numbering error: Renames files with a specific pattern in a given directory.
- Replace double dots: Replaces ".." occurrences in filenames within a given directory and its subdirectories.
- Remove last parentheses: Removes the last character from filenames within a given folder and its subfolders.
- Delete screenshot files: Deletes screenshot files within a given directory and its subdirectories.
- Organize files in format folders: Organizes multimedia files within a given root directory by their format.
- Move JSON to format folders: Searches for files containing folder names and moves them to the corresponding folder within a given root directory.
- Convert to lowercase: Converts all filenames within a folder and its subfolders to lowercase.
- Get format folders: Obtains a list of folders within a directory.
- Run commands with exiftool: Executes commands in folders using the exiftool command-line tool.
- Correct HEIC extension: Changes the extension of HEIC image files to JPEG.

## Requirements

To use this solution, you need to have the following dependencies installed:

- Python 3
- pandas
- pillow_heif

You also need to have the exiftool command-line tool installed on your system. You can download it from the [ExifTool website](https://exiftool.org/).

## Installation

1. Clone the repository:

```
git clone https://github.com/your-username/google-photos-metadata-export.git
```

2. Install the required Python packages:

```
pip install pandas pillow_heif
```

3. Download and install the exiftool command-line tool from the [ExifTool website](https://exiftool.org/).

## Usage

1. Export your multimedia files from Google Photos using Google Takeout. Make sure to select the option to include metadata in JSON format.

2. Extract the exported files to a directory on your local machine.

3. Update the `collect_all_json_info` function in the `main.py` script with the correct folder path where your JSON files are located.

4. Open a terminal or command prompt and navigate to the directory where you cloned the repository.

5. Run the `main.py` script:

```
python main.py
```

6. Follow the on-screen prompts to execute the desired tasks and organize your multimedia files.

## Contributing

Contributions to this project are welcome. You can contribute by submitting bug reports, suggesting new features, or implementing improvements. Please open an issue on the [GitHub repository](https://github.com/your-username/google-photos-metadata-export) to discuss potential changes or get involved.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
```

Feel free

.
