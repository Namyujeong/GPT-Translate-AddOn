# GPT-Translate-AddOn
GPT-Translate-AddOn is a Google Sheets add-on that enables seamless multilingual translations using OpenAI's GPT-4 model. This tool is designed to assist users in translating text across various languages directly within Google Sheets, enhancing productivity and collaboration.

## Features
- Seamless translation between multiple languages within Google Sheets.
- Activate or deactivate the translation feature from the menu.
S- upports various languages.

## Installation
- Install the add-on from Google Workspace Marketplace.
- Follow the detailed installation and publication guide here: [Google Workspace Marketplace How-To](https://developers.google.com/workspace/marketplace/how-to-publish).
- Open Google Sheets, go to "Extensions > GPT Translate" to activate.

<img width="738" alt="Screen Shot 2024-08-28 at 1 55 14 AM" src="https://github.com/user-attachments/assets/1c00dc51-9394-4615-ba6e-5309412c108d">


## Usage in Google Sheets
- Use the function `=gpt_translation("Your text", "LANGUAGE_CODE")` to translate text.
- Example: `=gpt_translation(A1, "KR")` translates the text in cell A1 to Korean.
- Replace `LANGUAGE_CODE` with the appropriate code (e.g., `"EN"` for English, `"KR"` for Korean).

<img width="359" alt="image (1)" src="https://github.com/user-attachments/assets/b15cfff5-010a-4ea6-9cd8-41cdbb933bc8">


## Customization

1. Enter Your OpenAI API Key:
- Replace `YOUR_API_KEY` in the script with your personal OpenAI API key.

2. Supported Languages:
- You can customize or extend this list by modifying the languageMap object in the script.
- The script includes a languageMap that supports the following languages by default:
  
```
EN: English
KR: Korean
PT: Portuguese
JA: Japanese
ES: Spanish
TH: Thai
ID: Indonesian
RU: Russian
ZH-CN: Chinese (Simplified)
ZH-TW: Chinese (Traditional)
TL: Tagalog
VI: Vietnamese
```

3. Customize UI:
- Modify the menu options in the script to fit your specific needs. The UI includes options to activate or deactivate the GPT Translate feature through the Google Sheets menu.

# License
This project is licensed under the MIT License.

# Contributions
Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.
