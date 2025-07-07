# DFS_pitchers
# 🎯 Top Pitchers to Stack Against - Daily MLB Analysis Tool

A web-based tool that analyzes MLB pitcher performance metrics to identify the most vulnerable pitchers for daily fantasy sports (DFS) stacking strategies. This tool highlights pitchers with poor performance indicators, making it easier to identify favorable matchups for opposing batters.

## 🌟 Features

- **Daily Data Updates**: Fetches current season pitcher statistics from FanGraphs
- **Smart Targeting System**: Automatically identifies pitchers with poor performance across 10 key metrics
- **Visual Performance Indicators**: Color-coded cells highlight vulnerable (red) and strong (green) statistics
- **Advanced Filtering**: Filter by minimum innings pitched, team, and number of target metrics
- **Sortable Columns**: Click any column header to sort and find specific patterns
- **Persistent Data**: Saves data locally for offline access and quick loading
- **Mobile Responsive**: Works seamlessly on desktop and mobile devices

## 📊 Key Metrics Analyzed

The tool evaluates pitchers based on these "target" thresholds:

| Metric | Target Threshold | Description |
|--------|-----------------|-------------|
| **K%** | < 20% | Low strikeout rate |
| **K/9** | < 7.0 | Few strikeouts per 9 innings |
| **K/BB** | < 2.5 | Poor strikeout-to-walk ratio |
| **xERA** | > 4.5 | High expected ERA |
| **ERA** | > 4.5 | High earned run average |
| **WHIP** | > 1.35 | High walks + hits per inning |
| **FIP** | > 4.5 | High fielding independent pitching |
| **Hard%** | > 35% | High hard contact rate |
| **HR/9** | > 1.5 | High home runs per 9 innings |
| **Barrel%** | > 10% | High barrel rate allowed |

## 🚀 Quick Start

### Option 1: Use GitHub Pages (Recommended)
1. Visit the live tool at: `https://[your-username].github.io/[repo-name]`
2. Click "Fetch Today's Data" or use manual update
3. Apply filters to find target pitchers
4. Sort by "Target Count" to see most vulnerable pitchers

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/[your-username]/pitcher-stack-analysis.git

# Open in browser
open index.html
# or
start index.html  # Windows
```

## 📥 How to Update Data

### Automatic Update (If Backend Configured)
1. Click "Fetch Today's Data" button
2. Wait for data to load
3. Data automatically saves to local storage

### Manual Update (Always Available)
1. Click the FanGraphs link (automatically includes today's date)
2. On FanGraphs page: Select all (Ctrl/Cmd + A) → Copy (Ctrl/Cmd + C)
3. Return to tool and paste in the text area
4. Click "Process Pasted Data"

## 🎮 Usage Guide

### Finding Target Pitchers
1. **Check Target Count**: Higher numbers (8-10) indicate very vulnerable pitchers
2. **Look for Red Cells**: Multiple red cells in a row suggest consistent vulnerability
3. **Filter by IP**: Set minimum innings to exclude small sample sizes
4. **Sort Strategically**: Click column headers to find specific weaknesses

### Best Practices for DFS
- Target pitchers with 6+ red metrics for GPP tournaments
- Consider ballpark factors (not included in tool)
- Check weather conditions separately
- Verify starting pitcher status before lineup lock

## 🛠️ Technical Details

### Technologies Used
- Pure JavaScript (no frameworks required)
- HTML5 & CSS3 with modern design
- LocalStorage for data persistence
- Responsive grid layout

### Data Source
- **FanGraphs**: Leading baseball statistics website
- **Update Frequency**: Daily during MLB season
- **Stats Coverage**: Current season only

## 📱 Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS/Android)

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs via Issues
- Suggest new features
- Submit pull requests
- Share feedback

### Development Setup
```bash
# No build process required - just edit and refresh!
# For server-side features, see server.js setup
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## ⚠️ Disclaimer

This tool is for informational purposes only. Always do your own research and gamble responsibly. Past performance does not guarantee future results.

## 🙏 Acknowledgments

- Data provided by [FanGraphs](https://www.fangraphs.com)
- Inspired by the DFS community's need for quick pitcher analysis
- Built with ❤️ for baseball analytics enthusiasts

---

**Questions?** Open an issue or reach out!

**Found it useful?** Give it a ⭐ on GitHub!
