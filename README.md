# Text and Document Content Summarization Chrome Extension

This Chrome extension provides AI-powered summarization capabilities for both webpage text and uploaded documents. It utilizes Google's Gemini model for generating summaries and key takeaways.

This template should help get you started developing with React in WXT.

# Features

## Text Summarization

- Summarize selected text
- Summarize entire webpage
- Generate key takeaways

## Document Summarization

- Support for .txt and .pdf files
- Intelligent document parsing
- Key points extraction

## Customizable Modes

- Brief: Quick, concise summaries
- Detailed: In-depth analysis
- Bullet Points: Organized key points
- Custom: User-defined prompts

# Chrome Built-In APIs Usage

## Translation Feature

This extension leverages Chrome's Built-In Translation API to provide seamless translation capabilities for summarized content.

![image](https://github.com/user-attachments/assets/519854b6-6e64-4ffb-b7f1-d7814239364f)
![image](https://github.com/user-attachments/assets/6e4e2bb8-1103-49fc-91dd-1cea89430975)

### Features

- Automatic Translation: Translates summaries into the target language specified in the extension settings.

- Supported Languages:

  - English (en)
  - Mandarin Chinese (Simplified) (zh)
  - Taiwanese Mandarin (Traditional) (zh-Hant)
  - Japanese (ja)
  - Portuguese (pt)
  - Russian (ru)
  - Spanish (es)
  - Turkish (tr)
  - Hindi (hi)
  - Vietnamese (vi)
  - Bengali (bn)

- User-Controlled Settings: Users can configure the source and target languages through the extension's settings.

### How to Enable Translation API

To use the translation features, ensure that Chrome's Translation API is enabled:

1. Open Chrome and navigate to chrome://flags.
2. Search for "Enable Translation API."
3. Set it to Enabled.
4. Restart Chrome to apply the changes.

## Install dependencies

`npm install`

## Create a .env file and add your Google AI API key

`echo "VITE_API_KEY=your_api_key_here" > .env`
*You need to add the translation_api key as VITE_TRANSLATE_API_KEY in your .env file too. 

## Run the program

`npm run dev`

After running npm run dev:

- A new Chrome window will automatically open
- The extension will be pre-installed in this window

# Usage

## Text Summarization

1. Selected Text

- Highlight any text on a webpage
- Right-click and select "Summarize Selection"

![image](https://github.com/user-attachments/assets/98805fc8-e78a-4591-be7f-8fa1d88c4a8f)

2. Full Page

- Right-click anywhere on the page
- Select "Summarize Full Page"

![image](https://github.com/user-attachments/assets/2d83dd13-1e8e-4f3a-9cdd-e839b298535e)

## Document Summarization

1. Upload Document

- Click the "+" button in the extension sidebar
- Select your document (.txt, .pdf, .docx)

## Customization Options

1. Summary Modes

![image](https://github.com/user-attachments/assets/6feb84f7-7cf9-44f8-a0ac-bc42e8702265)

- Brief: Default mode for quick summaries
- Detailed: Comprehensive analysis
- Bullet Points: Organized format
- Custom: Use your own prompt

## Key Features

- Dark/Light Mode: Automatic theme switching
- Copy to Clipboard: Easy sharing of summaries

![image](https://github.com/user-attachments/assets/7779cec4-db41-4bee-a04a-d76bb2e864fa)

- Key Takeaways: Separate section for important points
