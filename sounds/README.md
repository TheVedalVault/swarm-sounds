# Sounds Directory

This directory contains audio files for the Swarm Soundboard Bot.

## Supported Formats
- MP3 (.mp3)
- WAV (.wav) 
- OGG (.ogg)
- M4A (.m4a)
- FLAC (.flac)
- AAC (.aac)

## Adding Sounds

### Method 1: Interactive Script (Recommended)
```bash
npm run add-sounds-interactive
```
This will scan for new audio files and guide you through adding them with an interactive prompt.

### Method 2: Manual Single Addition
```bash
npm run add-sound "sound name" "filename.ext" "category" "person"
```

### Method 3: Direct Script
```bash
node addSound.js "sound name" "filename.ext" "category" "person"
```

## Categories
- `cursed` - Cursed/weird sounds
- `reactions` - Reaction sounds  
- `screams` - Scream/yell sounds
- `misc` - Miscellaneous sounds

## People
- `vedal` - Vedal987
- `neuro` - Neuro-sama
- `evil` - Evil Neuro
- `camila` - Camila
- `cerber` - Cerber
- `mini` - Mini
- `misc` - Other/Unknown

## Testing
To test the bot features, you can:
1. Add some audio files to this directory
2. Run `npm run add-sounds-interactive` to add them to the database
3. Build and start the bot with `npm run build && npm start`
4. Use `/play`, `/favorites`, `/queue` commands in Discord

## Sample Audio Files
For testing, you can use:
- Short sound effects from freesound.org
- Voice recordings (with permission)
- Creative Commons audio clips
- Text-to-speech generated samples
