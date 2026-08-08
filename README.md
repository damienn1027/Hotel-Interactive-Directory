# Youth Policy Lab - YMCA Hostel Directory

An interactive, 3D floor plan and live-synced directory web application designed to manage and visualize room allocations for the YMCA Hostel. Built for real-time logistics tracking, committee coordination, and streamlined check-ins.

---

## Features

* **Live Google Sheets Integration:** Automatically fetches and syncs room assignments, guest names, gender indicators, room types, and special remarks directly from a published Google Sheet backend via PapaParse.
* **3D Isometric & 2D Flat Views:** Seamlessly toggle between a dynamic 3D perspective floor plan and a clean 2D layout.
* **Dynamic Color-Coding:** Room blocks automatically paint themselves according to their room types (Twin, Double, Triple, Family) based on live backend data.
* **Live Search Bar:** Type any participant's name to instantly isolate and highlight their assigned room while dimming the rest of the floor plan.
* **Quick Filters:** Filter rooms instantly by status (All, Vacant, VIPs, Boys, Girls).
* **Click-to-Copy & Tooltips:** Hover over any room to view occupants in real-time, or click a room block to instantly copy its directory details to your clipboard with a confirmation toast notification.

---

## Getting Started & Deployment

1. **Host on GitHub:** Create a public repository on GitHub and upload your `index.html` file.
2. **Enable GitHub Pages:** 
   * Navigate to your repository **Settings > Pages**.
   * Under **Build and deployment**, select **Deploy from a branch** and point it to your main branch (`main` or `master`) root directory (`/`).
3. **Live Sync:** The app connects directly to your live Google Sheet using its published CSV endpoint. Any updates made in your spreadsheet will automatically reflect on the website upon refresh.
