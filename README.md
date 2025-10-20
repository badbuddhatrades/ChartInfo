# BBChartInfo - Chart Information Overlay

**Version:** v1.0.0.0
**Release Date:** October 19, 2025
**Developer:** BadBuddha Customs
**Platform:** NinjaTrader 8

---

## Overview

BBChartInfo is a lightweight NinjaTrader 8 indicator that displays essential chart information directly on your trading chart. Quickly identify the asset, timeframe, and current date without cluttering your workspace.

---

## Features

- **Real-time Chart Information Display**
  - Asset/Instrument name
  - Chart timeframe (e.g., Minute 5, Day 1)
  - Current bar date

- **Fully Customizable Appearance**
  - Choose text color
  - Adjustable opacity (0-100%)
  - Font size control (8-48 pixels)

- **Flexible Positioning**
  - Four corner positions: TopLeft, TopRight, BottomLeft, BottomRight
  - Fine-tune with horizontal and vertical offsets (-500 to +500 pixels)

- **Professional Features**
  - Automatic update checking
  - NinjaTrader 8.1.6+ vendor licensing support
  - Optimized SharpDX rendering

---

## Installation

### Requirements
- NinjaTrader 8 (8.1.6 or higher recommended)
- Windows 10 or later
- Valid BadBuddha Customs license (Product ID: 403)

### Steps

1. **Download** the latest BBChartInfo release from [BadBuddha Customs](https://badbuddhacustoms.com)

2. **Import into NinjaTrader:**
   - Open NinjaTrader 8
   - Go to `Tools` → `Import` → `NinjaScript Add-On`
   - Select the downloaded `.zip` file
   - Click `Import`

3. **Add to Chart:**
   - Right-click on any chart
   - Select `Indicators...`
   - Find "BBChartInfo" in the list
   - Click `OK`

---

## Configuration

### Display Settings

#### Text Color
- **Default:** White
- **Description:** Choose any color for the overlay text
- **Access:** Properties → Display Settings → Text Color

#### Text Opacity (%)
- **Default:** 80%
- **Range:** 0-100%
- **Description:** Control transparency (0 = invisible, 100 = fully opaque)

#### Font Size
- **Default:** 14 pixels
- **Range:** 8-48 pixels
- **Description:** Adjust text size for readability

#### Corner Position
- **Default:** TopLeft
- **Options:** TopLeft, TopRight, BottomLeft, BottomRight
- **Description:** Choose which corner to display the overlay

#### Horizontal Offset (pixels)
- **Default:** 0
- **Range:** -500 to +500 pixels
- **Description:** Fine-tune horizontal position (positive = right, negative = left)

#### Vertical Offset (pixels)
- **Default:** 0
- **Range:** -500 to +500 pixels
- **Description:** Fine-tune vertical position (positive = down, negative = up)

### Update Settings

#### Enable Update Check
- **Default:** Enabled
- **Description:** Automatically checks for new versions weekly

#### Show Update Popup
- **Default:** Enabled
- **Description:** Displays notification when updates are available

---

## Usage Examples

### Example 1: Top Left Corner (Default)
```
Corner Position: TopLeft
Horizontal Offset: 0
Vertical Offset: 0
```
Perfect for clean, unobstructed view in the upper left.

### Example 2: Bottom Right Corner
```
Corner Position: BottomRight
Horizontal Offset: 0
Vertical Offset: 0
```
Keeps information visible while preserving upper chart area for indicators.

### Example 3: Custom Position
```
Corner Position: TopRight
Horizontal Offset: -50
Vertical Offset: 20
```
Move slightly left and down from the top right corner to avoid overlap with other indicators.

---

## Displayed Information

The indicator shows three key pieces of information:

```
Asset: ES
Timeframe: Minute 5
Date: 10/19/2025
```

- **Asset:** The instrument's master name (e.g., ES, NQ, AAPL)
- **Timeframe:** The chart's bar period
- **Date:** The current bar's date in MM/DD/YYYY format

---


### Licensing Issues

If you see a licensing dialog:
- Check your NinjaTrader account at Tools → License Management
- Contact support@badbuddhacustoms.com for assistance

### Performance

BBChartInfo uses efficient SharpDX rendering and should have minimal performance impact. If you experience issues:
- Reduce font size
- Disable update checking if not needed

---

## Version History

### v1.0.0.0 (October 19, 2025)
- Initial release
- Basic chart information overlay
- Customizable appearance and positioning
- NinjaTrader 8.1.6+ vendor licensing support
- Automatic update checking

---

## Support

### Documentation
- GitHub: [BadBuddha ChartInfo Repository](https://github.com/badbuddhatrades/ChartInfo)
- Website: [https://badbuddhacustoms.com](https://badbuddhacustoms.com)

### Contact
- Email: info@badbuddhacustoms.com
- For licensing issues: support@badbuddhacustoms.com

### Updates
- Update manifest: [chartinfo_version.json](https://raw.githubusercontent.com/badbuddhatrades/ChartInfo/main/chartinfo_version.json)

---

## License

This software uses NinjaTrader's user-based vendor licensing system (8.1.6+). A valid BadBuddha Customs license is required for use.

**Vendor:** BadBuddhaCustoms
**Product Name:** BBChartInfo

---

## Technical Details

### Architecture
- **Platform:** NinjaTrader 8
- **Type:** Indicator (overlay)
- **Rendering:** SharpDX Direct2D
- **Update Service:** BadBuddha shared update service

**© 2025 BadBuddha Customs. All rights reserved.**
