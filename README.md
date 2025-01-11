I wrote this to reject the false sense of security offered by edit history. Make ya assignments creative and its a non-issue. 

# Auto-Type
UserScript Extension To Automatically Emulate Human Typing In Google Docs

# Google Docs Type Simulator

A userscript that simulates realistic human typing in Google Docs, complete with natural timing variations, occasional typos, and error corrections.

## Features

- Realistic typing simulation with variable speeds
- Natural typing patterns including key rollover and timing variations
- Configurable error rates and correction behavior
- Multiple typing profiles (Average, Fast, Slow)
- Advanced mode for fine-tuning all parameters

## Installation

1. Enable Chrome Developer Mode:
   - Open Chrome and go to `chrome://extensions/` (copy and paste this into your address bar)
   - Look for the "Developer mode" toggle in the top-right corner
   - Turn it ON

2. Install the Tampermonkey extension:
   - Go to the [Tampermonkey page on Chrome Web Store](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - Click "Add to Chrome"
   - Click "Add extension" in the popup
   - You should see the Tampermonkey icon appear in your Chrome toolbar

3. Install the userscript:
   - Click on the Tampermonkey icon in your Chrome toolbar
   - Select "Create a new script"
   - Delete any existing code in the editor
   - Copy and paste the entire content of `UserScript.js` into the editor
   - Press Ctrl+S (or Command+S on Mac) to save
   - You should see a notification that the script has been installed

4. Verify installation:
   - Click the Tampermonkey icon again
   - Select "Dashboard"
   - You should see "Google Docs Type Simulator" in your list of installed scripts
   - Make sure it's enabled (the switch should be ON)

## Usage

1. Open any Google Doc
2. Look for the "Type Simulator" button in the top toolbar
3. Click the button to open the simulator panel
4. Enter the text you want to type
5. Choose a typing profile or enable Advanced Mode for custom settings
6. Click "Start Typing" to begin the simulation

### Profiles

- **Average** (~52 WPM): Typical typing speed with occasional errors
- **Fast** (~75 WPM): Quick typing with more key rollover
- **Slow** (~25 WPM): Deliberate typing with fewer errors

### Advanced Mode

Advanced mode lets you customize:
- Base typing speed
- Timing variations
- Key overlap probability
- Error rates and correction behavior

## Troubleshooting

If the simulator button doesn't appear:
1. Make sure Tampermonkey is enabled
2. Try refreshing the Google Docs page
3. Check if the script is enabled in Tampermonkey's dashboard

## License

This project is licensed under the APACHE-2.0 License - see the LICENSE file for details.
I won't be stingy about giving you more rights if you ask me.

## Notes
The Time predictions are very off. I didnt fix them after adding the error correction action so it does not take that into account.
Its unfortunatly very slow, but hey thats human typing for you. You can turn the speed up if you want, but to be realistic it would be
good to add "thinking" pauses.

If you feel inclined you should hook this up to an agent. I like the idea but have cooler agents to make. 

