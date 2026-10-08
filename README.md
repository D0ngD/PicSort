# Mobile Photo Sorter

Organize photos and videos stored on your Windows PC directly from your phone browser.


---

## Features

- Browse photos and videos from your Windows PC using a phone browser
- Works over LAN, Wi-Fi, or a mobile hotspot
- Automatically scans subfolders

---

## Download

Go to **[Releases](../../releases)** and grab the ZIP file.

---

## Requirements

- Windows 10 or Windows 11
- Node.js LTS
- Your phone and PC must be connected to the same local network

---

## Usage

### Start the Application (All Versions)

1. Install Node.js LTS.
2. Extract the ZIP file.
3. Double-click `start.bat`.
4. On the first launch, the required packages will be installed automatically.
5. Keep the command window open while using the application.
6. Open the displayed local IP address on your phone browser.

Your phone and PC must be connected to the same local network.

### Version 1
Version 1 provides the basic photo browsing workflow.
You can:
- Connect to the PC from your phone browser
- Browse photos stored on the PC
- View photos without transferring them to the phone
- Remove unwanted photos from the browsing interface
This version focuses on basic connectivity and photo browsing.

### Version 2
Version 2 adds gesture-based photo sorting.
Gestures:
- Swipe up: Move to Pending Delete
- Swipe left: Previous photo
- Swipe right: Next photo
- Double tap: Move to Favorites
Version 2 also introduces two automatically managed folders:
- Favorites
- Pending Delete

### Version 3
Version 3 adds folder mode switching from the top navigation bar.
You can switch between:
- Photo Sorter
- Favorites
- Pending Delete

### Version 4
Version 4 adds several usability improvements:
- Undo the previous move action
- Thumbnail overview
- Restore files from Favorites or Pending Delete
- Remember the last viewed position
- Preload nearby images for smoother browsing
- View file information such as:
  - File name
  - File size
  - Resolution
  - File path
  - File timestamp

---

## FAQ

### My phone cannot connect to the PC

First confirm that the application works locally on the PC:

```text
http://localhost:3000
```

Then make sure your phone and PC are connected to the same network.

On Windows, run:

```powershell
ipconfig
```

Find the IPv4 address of the active network adapter.

Example:

```text
192.168.1.100
```

Then open this address on your phone:

```text
http://192.168.1.100:3000
```

---

## Version Comparison

| Version | Features |
|---|---|
| V1 | Basic mobile browsing and delete workflow |
| V2 | Swipe gestures, Favorites, Pending Delete |
| V3 | Top navigation for Photo Sorter / Favorites / Pending Delete |
| V4 | Undo, thumbnail overview, restore to original location, file info, preload, remember last position |

---

## License

- Free for personal use
- Redistribution allowed (must include source GitHub link)
- Commercial use prohibited
