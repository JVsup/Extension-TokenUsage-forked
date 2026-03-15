# Token Usage Tracker

![Extension Screenshot](1.png)

A SillyTavern extension that tracks and visualizes token usage and price for your chats.

## Installation

1.  Open SillyTavern and navigate to the **Extensions** menu (blocks icon).
2.  Click on **Install Extension**.
3.  Paste the repository URL into the "Extension URL" field:
    ```
    https://github.com/Vibecoder9000/Extension-TokenUsage
    ```
4.  Click **Install for all users** or **Install just for me**.

## Usage

Once installed, the extension will automatically start tracking token usage. The GUI will be in the extensions menu.

## License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). See the `LICENSE` file for details.

---------------

## Notes and Changelog for this fork

- Created with heavy AI assistance. It works for me, hopefully it will work for you too.
- My main focus was better UI/UX and improved OpenRouter integration.
- Note on Accuracy: This extension estimates costs using SillyTavern's internal tokenizers (I left original logic alone). For models that fall back to the default GPT-3 counter, accuracy will vary. Always refer to your API provider's dashboard for definitive billing.

![Image](https://github.com/user-attachments/assets/9562e3b6-185d-49df-926c-33680c9667f4)

### v1.2.0 (2026-03-15)
- **Top Bar Integration**: Seamless icon placement next to native API settings.
- **Enhanced Tooltip**: Quick-look stats including session costs and per-model breakdown.
- **Auto-Pricing**: OpenRouter prices are now fetched automatically and filled for models that doest have prices already set in configuration dialog.
- **Charts**: Added a 24h view and general visual polish to the dashboard.
- **Auto-pick week end**: Pick Sun/Mon as end of the week based on browser locale.
