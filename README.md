![Screenshot_20241021_154630_com android chrome](https://github.com/user-attachments/assets/8b654e45-dc2c-4b57-aa51-75ad596b7a4a)
![Screenshot_20241021_162540_com android chrome](https://github.com/user-attachments/assets/4f315d1a-b2e5-4dac-ad98-37e4736fa8c2)
![Screenshot_20241021_164816_com android chrome](https://github.com/user-attachments/assets/8adddf24-2370-46cd-a2c5-070fefcb2789)
![OKX_1728705152927](https://github.com/user-attachments/assets/78e7fdb1-eee8-4d13-957d-5b947fe8eda3)
![Screenshot_20241021_164742_com android chrome](https://github.com/user-attachments/assets/2eeb7df6-86da-4565-8c18-a169e8ccabd3)
# Thinking Claude

Let Claude think comprehensively before responding!

> **a super quick reminder:**
> thinking claude **is not aimed for benchmarks or huge leaps in math or something**, since they are pre-determined by the base model (new Claude-3.5 Sonnet).
> i only want to explore how further we could reach with Claude's "deep mindset". that's said, when using it in your daily tasks, you would found Claude's inner monolog (thinking process) very very fun and interesting.

## Demo:



https://github.com/user-attachments/assets/c3532383-e3fa-4d06-b9e3-89160fff8986



## Overview

This project consists of two main components:
1. **Thinking Protocol**: A comprehensive set of instructions that guides Claude to think deeply and systematically before responding
2. **Browser Extension**: A tool that makes Claude's thinking process more readable and manageable in the browser interface

## Thinking Protocol

The thinking protocol instructs Claude to follow a natural, thorough thought process before providing responses.

## Browser Extension

The browser extension enhances the Claude interface by making the thinking process more manageable:

### Features
- 🔄 Collapsible thinking process sections
- 📋 Easy copy functionality
- 🎯 Clean and intuitive interface
- ⚡ Automatic processing of new messages

### Installation

#### Chrome
1. Clone this repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode"
4. Click "Load unpacked" and select the `extension/chrome` folder

#### Firefox
1. Clone this repository 
2. Open Firefox and navigate to `about:debugging#/runtime/this-firefox`
3. Click "Load Temporary Add-on"
4. Navigate to the repository and select the `extension/firefox/manifest.json` file

## Usage

### Applying the Thinking Protocol

1. Copy the contents of `model_instructions.md`
2. Start a new Project in Claude.ai
3. Paste the instructions to the Custom Insructions section
3. Claude will now follow the thinking protocol for all subsequent interactions

### Using the Extension

Once installed, the extension automatically:
- Detects Claude's thinking process blocks
- Adds collapse/expand functionality
- Provides a copy button for each block

## Why Use Thinking Claude?

- **Better Reasoning**: Get more thorough and well-thought-out responses
- **Transparency**: See how Claude arrives at its conclusions
- **Improved Organization**: Manage long conversations more effectively
- **Quality Control**: Benefit from built-in verification steps

## Contributing

Contributions are welcome! Feel free to:
- Submit bug reports
- Propose new features
- Create pull requests

## License

MIT License - feel free to use and modify as needed.

## Acknowledgments

Special thanks to Claude! We build this whole extension together!
