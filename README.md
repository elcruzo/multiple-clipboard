# ElCruzo's Multiple Clipboard Holder Tool

Welcome to this repository containing an open-source multi-clipboard holder tool!

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Usage](#usage)
- [Example](#example)
- [Installation](#installation)
- [Customization](#customization)
- [Notes](#notes)
- [License](#license)
- [Author](#author)

## Description
The Multiple Clipboard Holder Tool is a Python script that allows you to manage and switch between multiple clipboard entries on your Windows system. It provides a convenient way to store and recall clipboard contents, making it easier to work with different pieces of copied text.

## Features
- Store up to five different clipboard entries.
- Easily switch between stored clipboard entries.
- Automatically updates the clipboard with the selected entry.
- Continuous monitoring of the system clipboard to track changes.

<i>However, this script only works for Windows OS because we are importing a windows library</i>

## Usage
1. Run the script in a Python environment (e.g., using `python index.py`).

2. The tool will continuously monitor your system clipboard for changes.

3. To save a clipboard entry:
   - Copy a piece of text to your clipboard.
   - Press a number key (0-4) corresponding to the slot where you want to store the clipboard entry.
   
4. To recall a stored clipboard entry:
   - Press the number key (0-4) corresponding to the slot you want to retrieve.
   - The clipboard will be updated with the stored entry.

5. You can switch between different clipboard entries quickly and efficiently.

## Example
- Copy a URL to clipboard.
- Press '1' to save it to slot 1.
- Copy a different URL to clipboard.
- Press '2' to save it to slot 2.
- Press '1' to recall the first URL and paste it.
- Press '2' to recall the second URL and paste it.

Certainly! Here's an additional subheading that allows users to customize the multiple clipboard holder tool:

## Customization
You can easily customize the behavior of the Multiple Clipboard Holder Tool to fit your specific needs. Here's an example of how you can customize it:

### Example: Changing the Number of Slots
By default, the tool supports up to five slots for storing clipboard entries. If you want to increase or decrease the number of slots, you can do so by modifying the script. 

1. Open the `index.py` script in a text editor.

2. Locate the `clips` list near the beginning of the script. It looks like this:
   ```python
   clips = ["", "", "", "", ""]
   ```
   
3. You can add or remove slots by modifying this list. For example, to have three slots, you can change it to:
   ```python
   clips = ["", "", ""]
   ```

4. Save the script.

5. When you run the modified script, it will have the updated number of slots.

6. Feel free to explore the script and make other customizations to suit your preferences and workflow.

## Notes
- The tool uses the `win32clipboard` library to interact with the Windows clipboard.
- It supports up to five slots for storing clipboard entries.
- The tool continuously runs in the background to monitor clipboard changes.
- You can customize the number of slots or storage behavior as needed by modifying the script.

## License
This Multiple Clipboard Holder Tool is open-source software licensed under the [MIT License](LICENSE).

## Author
[ElCruzo](https://github.com/elcruzo)

---

Enjoy using the Multiple Clipboard Holder Tool, and feel free to contribute to its development or customize it to suit your needs!
