# Workout Viz - Push Day

A mobile-first workout visualization app built with Preact. Features stunning data visualizations for your workout data including heart rate charts, volume progression, intensity heatmaps, and a Strava-like shareable summary card.

## Features

- **Heart Rate Chart** - Animated SVG chart showing BPM progression during cardio
- **Volume Progression** - Bar chart showing weight × reps across sets
- **Intensity Heatmap** - Color-coded exercise intensity visualization
- **Workout Flow** - Visual timeline of exercises with sets
- **Share Card** - Strava-style summary card perfect for screenshots

## Tech Stack

- Preact (via CDN)
- HTM for JSX-like templating
- Pure CSS with CSS variables
- Single HTML file - no build step needed

## Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Upload `index.html` to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose `main` branch
5. Your app will be live at `https://yourusername.github.io/repo-name/`

### Netlify Drop

1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag and drop the `workout-viz` folder
3. Get an instant live URL

### Vercel

```bash
npm i -g vercel
vercel --prod
```

## Workout Data

The app visualizes a Push Day workout:
- 7 exercises (Push ups, Chest Press, Cable Fly, Arnold Press, Lateral Raises, Tricep Extension, Tricep Kickback)
- Cardio session (30:33 duration, 2.86km, 245 cal, 142 BPM avg)

## Customization

Edit the `workoutData` object in the script section to use your own workout data.

## Screenshot

The app is designed to look great when screenshotted - perfect for sharing to Instagram Stories, Strava, or WhatsApp status!