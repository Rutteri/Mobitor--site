# Assets Directory

## App Icon

Place your app icon here as `app-icon.png` to display it on the homepage.

### Recommended Specifications:
- **Format**: PNG or WebP
- **Size**: 512x512 pixels (or larger, will be scaled down)
- **File name**: `app-icon.png`

### Getting the Icon from CustomDashboard Repository:

If you want to use the actual Mobitor app icon from the CustomDashboard repository:

1. Navigate to the CustomDashboard repository
2. Find the launcher icon at: `app/src/main/res/mipmap-xxxhdpi/ic_launcher.png` (or similar mipmap directory)
3. Copy the PNG file to this directory and rename it to `app-icon.png`

Example command:
```bash
cp /path/to/CustomDashboard/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png ./assets/app-icon.png
```

### Alternative: Use SVG

If you prefer to use an SVG icon:
1. Update the `src` attribute in `index.html` from `assets/app-icon.png` to `assets/app-icon.svg`
2. Place your SVG file here as `app-icon.svg`

## Other Assets

You can place other images, icons, or media files in this directory as needed.
