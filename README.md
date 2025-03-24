# DO-CLI-Sampler

A modern web application for creating and managing Day One journal entries using the Day One Command Line Interface (CLI).

![Day One CLI Entry Creator](https://github.com/user-attachments/assets/82e04c80-f477-4002-af04-5b79856a8fab)


## Features

- 🎭 **User Bio System**: Select from a collection of pre-configured user bios including name, occupation, and personal details
- 📝 **Random Entry Generation**: Create sample journal entries with a single click
- 🏷️ **Flexible Tagging**: Add both built-in and custom tags to your journal entries
- 📅 **Custom Date Support**: Specify custom dates and times for your entries
- 🎨 **Theme Customization**: Choose from 12 different themes with the built-in theme switcher
- 🖥️ **CLI Command Preview**: See exactly what command will be used to create your entry
- 🔄 **Real-time Updates**: UI updates in real-time as you make changes

## Prerequisites

- [Node.js](https://nodejs.org/) (v14 or newer)
- [Day One CLI](https://dayoneapp.com/guides/documentation/cli-documentation) installed
- Day One app for macOS

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/DO-CLI-Sampler.git
   cd DO-CLI-Sampler
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the application:
   ```bash
   npm start
   ```

4. Open your browser to the URL shown in the terminal (typically http://localhost:3003)

## Usage

### Creating an Entry

1. Select a user bio from the dropdown
2. Click "Create Entry" to generate a random journal entry
3. Edit the entry text if desired
4. Optionally add tags or set a custom date
5. Click "Save to Day One" to add the entry to your journal

### Tag Management

- The "DOSampleEntry" tag is applied to all entries by default
- Select additional built-in tags by checking the corresponding boxes
- Add custom tags by entering them in the custom tags field, separated by commas

### Custom Dates

- Check "Use custom date for entry" to specify a custom date
- Select the desired date and time using the date picker

### Themes

- Click the "Theme" button in the top left to select from different themes
- The theme selection is saved between sessions

## Technical Details

This application uses:

- Express.js for the backend server
- DaisyUI and Tailwind CSS for the interface
- Day One CLI for journal interactions
- Modern JavaScript with async/await patterns

## File Structure

- `index.html` - The web interface
- `server.js` - Express server that handles Day One CLI commands
- `sample-bio.json` - Collection of user bios
- `sample-entries.json` - Sample journal entry texts
- `docli-documentation.md` - Documentation for the Day One CLI

## License

MIT License
