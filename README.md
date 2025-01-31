# gdrive-sync-uploader

## Overview
GDrive-Auto-Upload is a Python script designed to automate the process of uploading files and directories to Google Drive. It allows you to specify a local source folder and a destination folder on Google Drive, enabling seamless file transfer without manual intervention.

## Prerequisites
Before running the script, ensure that you have Python installed, along with the required libraries. Additionally, you'll need to have `pip` installed for managing dependencies.

### Installation Steps
1. Clone this repository or download the script files to your local machine.
2. Install the required Python libraries by running the following command:
   ```bash
   pip install -r requirements.txt
   ```
   This will automatically install all dependencies listed in the `requirements.txt` file.

## Usage
1. Set up Google Drive API credentials (follow [this guide](https://developers.google.com/drive/api/v3/quickstart) to obtain the necessary credentials).
2. Update the script with the path to your source folder and the destination folder ID on Google Drive.
3. Run the script to start the automatic upload process.
