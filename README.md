# Text File Compressor and De-compressor Web App

This web application leverages **Huffman Coding** for effective text compression and decompression.

**Technologies Used:** JavaScript, HTML5, CSS3


## About This Application

### Overview

This web app facilitates **lossless data compression** and **decompression** of text files (.txt) using the **Huffman Coding Algorithm**. The core principle behind Huffman Coding is to use variable-length codes for different characters based on their frequency of occurrence in the text. Characters that appear more frequently are assigned shorter codes, while those that are less frequent get longer codes. This results in a more compact representation of the text data.

### How Huffman Coding Works

1. **Frequency Analysis:** The algorithm begins by analyzing the frequency of each character in the input text.
2. **Building the Tree:** A binary tree is constructed, where each leaf node represents a character and its frequency. The tree is built from the bottom up, with more frequent characters closer to the root.
3. **Assigning Codes:** Each character is assigned a binary code based on its position in the tree. Characters closer to the root receive shorter codes.

### Key Features

- **Lossless Compression:** The app ensures that no data is lost during the compression process. The original text can be perfectly reconstructed from the compressed file.
- **Responsive Design:** The application is designed to be responsive, providing a seamless user experience across various devices (desktops, tablets, and smartphones).
- **Interactive Interface:** Built with JavaScript to provide a dynamic and user-friendly interface. Users can easily compress and decompress text files with just a few clicks.
- **Educational Info Page:** An **Info Page** is included to offer more insights into the Huffman Coding technique and the principles of lossless data compression.

### Benefits

- **Efficiency:** Huffman Coding can achieve significant compression ratios, especially for larger files with many repeating characters.
- **User-Friendly:** The web app’s intuitive design makes it accessible for users with varying levels of technical expertise.

### Future Enhancements

- **Support for More File Formats:** Plans to extend support for other file types beyond .txt.
- **Enhanced User Interface:** Ongoing improvements to the UI for an even more seamless user experience.

Feel free to explore the live demo and see the Huffman Coding algorithm in action!
