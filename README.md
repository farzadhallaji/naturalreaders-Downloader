# NaturalReaders Downloader

This repository provides a simple way to download audio files generated by NaturalReaders.

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Google Chrome (or another browser of your choice)
- ChromeDriver (or corresponding WebDriver for your browser)
- Required Python packages: `selenium`

## Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/naturalreaders-downloader.git
   cd naturalreaders-downloader
   ```

2. **Install Required Packages:**
   You can install the required Python packages using `pip`:
   ```sh
   pip install selenium
   ```

## Usage

1. **Generate Audio:**
   - Open the Jupyter notebook in this repository.
   - Execute the first cell in the notebook.
   - Type your text in the NaturalReaders input field and click the play button.
   - Wait for the audio to finish playing all sentences.

2. **Retrieve Blob URLs:**
   - Execute the second cell to capture the Blob URLs of the generated audio files.

3. **Download Audio Files:**
   - Execute the third cell to download the audio files. The files will be saved to your specified folder.

## Additional Information

- Ensure you have all required dependencies installed and properly configured.
- Customize the `folder_path` and `file_name_base` variables in the script to define where and how your audio files will be saved.

## Keywords
NaturalReaders, Audio Downloader, Text to Speech, Selenium Automation, Python, Jupyter Notebook, ChromeDriver, Web Scraping, Download Audio Files

## Contact
For any issues or questions, please open an issue on [GitHub](https://github.com/farzadhallaji/naturalreaders-downloader/issues).


