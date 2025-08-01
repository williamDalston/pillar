# Pillar: Your Daily Foundation

A beautiful, modern web app for your daily wellness routine with journaling, stretching, strength training, and meditation.

## Development

To start development with live CSS rebuilding:

```bash
npm run build
```

This will watch for changes and automatically rebuild the CSS.

## Production

To build for production (minified CSS):

```bash
npm run build:prod
```

## Project Structure

- `index.html` - Main application file
- `input.css` - Tailwind CSS source file
- `dist/output.css` - Compiled CSS (generated)
- `tailwind.config.js` - Tailwind configuration

## Features

- **Journal**: Daily prompts for reflection
- **Stretch**: 10-minute guided stretching routine
- **Strength**: 14-minute full-body workout
- **Meditation**: 12-minute guided meditation

The app automatically resets progress daily and saves your journal entries locally. 