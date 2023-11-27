# Bulk File Renaming Script

A simple Node.js script for bulk renaming files in a directory by replacing specified strings.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Parameters](#parameters)
- [Examples](#examples)
- [License](#license)

## Introduction

This script is designed to streamline the process of bulk renaming files within a specified directory. It uses Node.js and the File System (`fs`) module to traverse the directory, identify files, and rename them by replacing specified strings.

## Features

- **String Replacement**: Replace occurrences of a specified string in each file name.
- **Preview Mode**: Option to preview changes before applying them to the files.
- **Console Feedback**: Provides feedback in the console, indicating the success of each renaming operation.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/subrat29/Bulk-Rename.git
   ```
   
   ```bash
   cd Bulk-Rename
   ```

2. **Install Dependencies**
No dependencies are required for this script.

3. **Run the Script**
    ```bash
    node index.js
    ```

## Parameters

The script accepts the following parameters:

- **replaceThis:**  
  The string to be replaced in file names.

- **replaceWith:**  
  The string to replace occurrences of `replaceThis`.

- **preview:**  
  A boolean flag indicating whether to preview changes without applying them.

- **folder:**  
  The path to the target directory. The script will operate within this directory.



# Examples

## Example 1: Perform Renaming (Without Preview)
```bash
node index.js
```

## Example 2: Preview Changes
```bash
node index --preview
```

## Example 3: Customize Replace Strings
```bash
node index.js --replaceThis "oldString" --replaceWith "newString"
```

# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.🫡🤝