# Sydney MyRTA Booking System Monitoring and Alerting System

A browser extension that monitors the Sydney MyRTA booking system for visual changes and alerts you instantly when booking availability changes.

## 📖 Detailed Guide and Step-by-Step Process

For a comprehensive interactive guide with detailed step-by-step instructions, visit:

**[👉 View Detailed Guide](https://robinthomasonline.github.io/apps/sydney_myrta_booking_system_monitoring_system/)**

The detailed guide includes:
- Interactive step-by-step installation process
- Browser compatibility information
- Configuration settings
- Troubleshooting tips
- And much more!

## Quick Start

1. **Download** the extension ZIP file
2. **Unzip** the packed extension
3. **Enable Developer Mode** in your Chrome-based browser
4. **Load the unpacked extension**
5. **Login** to MyRTA website and navigate to the change date screen
6. **Open the extension** and click "Use Current Tab"
7. **Enable "Refresh page before checking"** and set **Refresh Interval to 600 seconds (10 minutes)**
8. **Click "Start Monitoring"**

The extension will automatically refresh the page every 10 minutes and alert you when booking availability changes are detected.

## Step-by-Step Installation Guide

### Step 1: Download Extension

Download the browser extension ZIP file to get started.

**Download Link**: [sydney_myrta_booking_system_monitoring_system.zip](https://robinthomasonline.github.io/apps/sydney_myrta_booking_system_monitoring_system/sydney_myrta_booking_system_monitoring_system.zip)

> **After downloading:** Extract the ZIP file to a folder on your computer. You'll need this folder in the next steps.

### Step 2: Check Browser Compatibility

This extension works in Chrome-based browsers:

- **Google Chrome**
- **Microsoft Edge**
- **Brave Browser**
- **Opera**
- **Vivaldi**
- **Chromium**

> **Note:** Firefox and Safari are not supported as they use different extension APIs.

### Step 3: Enable Developer Mode

To install the extension, you need to enable Developer Mode in your browser.

1. Open your browser's Extensions page:
   - Navigate to `chrome://extensions/` (or `edge://extensions/` for Edge)
   - Or go to **Menu → More Tools → Extensions**

2. Toggle the **"Developer mode"** switch in the top-right corner of the Extensions page

> **Developer Mode** allows you to load unpacked extensions from your computer.

### Step 4: Load the Extension

Now load the unpacked extension from the folder you extracted earlier.

1. On the Extensions page, click the **"Load unpacked"** button
2. Select the folder containing the extracted extension files (the folder you unzipped in Step 1)
3. The extension will appear as **"Booking System Monitor"** in your extensions list

> **Tip:** Make sure you select the folder that contains the extension files (manifest.json, etc.), not the ZIP file.

### Step 5: Pin the Extension (Recommended)

Pin the extension to your browser toolbar for easy access.

1. Click the **puzzle icon** in your browser toolbar (extensions menu)
2. Find **"Booking System Monitor"** in the list
3. Click the **pin icon** next to it to keep it visible in your toolbar

> **Why pin it?** Having the extension icon visible makes it easier to access when configuring and monitoring.

## Usage Guide

### Step 6: Book a Test with Any Available Date

Book a test with any available date to get started.

1. Navigate to the MyRTA Login page:
   - **Login Page**: https://www.myrta.com/wps/portal/extvp/myrta/licence/tbs/tbs-login
2. Log in with your MyRTA credentials
3. Book a test with any available date

> **Note:** You need to have an existing booking to change the date. Book with any available date first.

### Step 7: Navigate to Change Date Screen

Go to the page you want to monitor for booking availability changes.

1. Navigate to the Change Date page:
   - **Change Date Page**: https://www.myrta.com/wps/portal/extvp/myrta/licence/tbs/tbs-change
2. Log in with your booking details
3. Select the location
4. **Zoom out the page** (press `Ctrl + -` or `Cmd + -` on Mac) so the date change section is fully visible on your screen
5. Make sure the entire date selection area is visible without scrolling

> **Important:** The extension monitors visual changes on this page. Make sure the date selection area is fully visible for accurate monitoring.

### Step 8: Configure Extension Settings

Open and configure the extension with the recommended settings.

1. Click the **"Booking System Monitor"** extension icon in your browser toolbar
2. Click **"Use Current Tab"** to capture the MyRTA page URL
3. Configure the following settings:
   - ✅ Check **"Refresh page before checking"**
   - Set **Refresh Interval to 600 seconds (10 minutes)**
   - ✅ Enable **"Play sound alert"**
   - ✅ Enable **"Desktop notification"**

#### Recommended Settings Summary

- **Refresh Interval**: **600 seconds (10 minutes)**
- **Pixel Threshold**: 1000 (default)
- **Sound Alert**: Enabled
- **Desktop Notification**: Enabled

### Step 9: Start Monitoring

Start the monitoring process and view statistics.

1. Click **"Start Monitoring"** in the extension popup
2. The status will show **"Monitoring"** with a green dot
3. The page will automatically refresh every 10 minutes to check for changes

#### View Statistics

While monitoring, you can see:
- Last check time
- Next check time
- Number of changes detected
- Last change timestamp

#### Stop Monitoring

To pause monitoring:
- Click **"Stop Monitoring"** in the extension
- Your settings will be saved automatically

> The extension will automatically refresh the page every 10 minutes and alert you when booking availability changes are detected.

### Step 10: Monitor and Update Your Booking

Once monitoring is active, you can continue with your daily activities while the system watches for new dates.

1. **Engage in your day-to-day activities** - The extension will continue monitoring in the background
2. When new dates appear on the screen, the system will alert you with:
   - A **sound alert**
   - A **desktop notification**
3. When you receive an alert, check the available dates
4. **Change to the available next date** if it suits your schedule
5. **Repeat this process** until you get the comfortable/required date for your testing

> **Tip:** The extension runs in the background, so you can work on other tasks while it monitors for new booking dates. You'll be notified immediately when changes are detected.

> **Remember:** Act quickly when you see a desirable date, as slots may be taken by others. The extension helps you catch new dates as soon as they become available.

## Troubleshooting

### Extension Not Working

- Make sure the extension is enabled in `chrome://extensions/`
- Try reloading the extension by clicking the reload icon on the Extensions page

### No Changes Detected

- Lower the pixel threshold if needed (in extension settings)
- Make sure you're on the correct MyRTA page (Change Date page)
- Make sure the date change section is fully visible on screen (zoom out if needed)

### Notifications Not Showing

- Check browser notification settings: `chrome://settings/content/notifications`
- Make sure "Desktop Notification" is enabled in extension settings
- Allow notifications for your browser when prompted

## Important Disclaimer

**Use Responsibly:** This is a browser page visual change monitoring plugin. This extension:

- Only monitors visual changes on the MyRTA booking page
- Alerts you when new dates appear on the screen
- Does NOT create new booking slots
- Does NOT have any connection to Service NSW or any other government organization
- Does NOT manipulate or interfere with the booking system

This extension is simply a monitoring tool that helps you stay informed about available dates. It does not create slots, modify the booking system, or have any affiliation with government services. Use it responsibly and in accordance with the terms of service of the MyRTA website.

## Support

If you find this plugin helpful, please consider supporting its development:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/robinthomasonline)

**Buy Me a Coffee**: [https://buymeacoffee.com/robinthomasonline](https://buymeacoffee.com/robinthomasonline)

### Share with Someone in Need

Know someone who's struggling to find a booking slot? Share this extension with them so they can monitor for available dates and get notified when new slots become available.

---

**Developed By:** [Robin Thomas](https://robinthomasonline.github.io/)
