# Caravan Landing Page - Project Brief

## 🎯 Goal
Create a modern, high-performance landing page for **Caravan Field Recorder**, an offline-first archaeological data collection tool.

## 📝 Project Identity
- **Name**: Caravan Field Recorder
- **Tagline**: "The Offline-First Digital Field Recorder for Modern Archaeology"
- **Key Value Props**:
  - **Offline-First**: Built for remote grid squares without signal.
  - **Cloud Sync**: Seamless background synchronization when back online.
  - **Data Integrity**: Controlled vocabularies and flexible schemas.
  - **Spatial Context**: Integrated GIS mapping.

## 🛠 Recommended Tech Stack
- **Framework**: **Astro** (Best for static landing pages, incredibly fast) or **Next.js**.
- **Styling**: **Tailwind CSS** (visual consistency with the main app).
- **Deployment**: Vercel or GitHub Pages.

## 📋 Implementation Steps
1. **Initialize Project**: Scaffold a new web project in the `caravan-corridors-landing` directory.
2. **Design System**: Set up the same font (Inter) and color palette (Indigo/Slate) as the desktop app.
3. **Sections Needed**:
   - **Hero**: High-impact headline + "Download" buttons + Screenshot of the App.
   - **Features Grid**: Cards detailing Sync, Map, and Custom Columns.
   - **How it Works**: Simple 1-2-3 step guide (Install -> Collect -> Sync).
   - **Open Source**: Link to the main GitHub repository.
   - **Footer**: Copyright and Links.

## 🚀 How to Start
1. Open the `/Users/hannahfarrell/Coding/Antigravity/caravan-corridors-landing` folder in your editor.
2. Ask the AI: "Initialize a new Astro project with Tailwind."

## 🔧 Technical Specifications & Context (Auto-Generated)

### Design System & Assets
- **Font:** `Inter` (Sans-serif)
- **Tailwind Config:** The app uses custom animations you should replicate:
  - `float`: `float 3s ease-in-out infinite`
  - `gradient-shift`: `gradient-shift 6s ease infinite`
- **Theme:** The app supports **Dark/Light mode**. The landing page should reflect this dark, modern aesthetic.

### Corrected Feature Set (For Copywriting)
1.  **"Offline-First"**: True. Local SQLite databases.
2.  **"Cloud Backup"**: preferred over "Real-time Sync". The system backs up files when online.
3.  **"Customizable"**: Users can add their own columns (dynamic schema).
4.  **"Map Integration"**: Integrated Leaflet maps for visualization.

### Recommended Visuals
Since no screenshots exist, generate **Dark Mode** UI mockups showing:
- A data grid with columns: `Artifact ID`, `Context`, `Material`, `Condition`.
- A split view with a map showing markers.
