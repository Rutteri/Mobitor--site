# Icon Replacement Note

The current `mobitor-icon.svg` is a placeholder. 

To use the actual app launcher icon from CustomDashboard:
1. Clone the CustomDashboard repository
2. Find the launcher icon in `app/src/main/res/mipmap-*/ic_launcher.png`
3. Copy the high-resolution PNG (e.g., from xxxhdpi) to this directory as `mobitor-icon.png`
4. Update `index.html` to reference `/assets/mobitor-icon.png` instead of `/assets/mobitor-icon.svg`
