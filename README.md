# The Shield - Mission Section

This Jekyll site includes a beautifully designed mission section that recreates the design you provided.

## Structure

- `_includes/home-mission.html` - The main mission section component
- `assets/css/mission.css` - Styling for the mission section
- `index.html` - Homepage that includes the mission section
- `_layouts/default.html` - Base layout template

## How to Use

### Running the Site

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Start the Jekyll server:
   ```bash
   bundle exec jekyll serve
   ```

3. Open your browser to `http://localhost:4000`

### Including the Mission Section

To add the mission section to any page, simply include it:

```liquid
{% include home-mission.html %}
```

## Features

- Responsive design that works on all screen sizes
- Animated cityscape with buildings and windows
- Person sitting on a bench illustration
- Semi-transparent mission card with blur effect
- Palm leaf decorations
- Custom signature graphic
- Dark teal theme matching the provided design

## Customization

You can customize the content by editing `_includes/home-mission.html` and adjust styles in `assets/css/mission.css`.
