# Questions & Answers for Caravan Project Team

The following answers are based on a technical analysis of the current `caravan-corridors-database` codebase.

## 1. Product Identity & Scope
*   **App vs. Schema:**
    *   **Answer:** The primary downloadable product is the **"Caravan Field Recorder"** (the App). The "Caravan Corridors" name refers to the underlying database schema and the broader research project.
    *   **Recommendation:** Pivot the landing page to sell the "Caravan Field Recorder" app as the tool users download, while mentioning it enforces the "Caravan Corridors" data standard.

*   **Naming:**
    *   **Answer:** They are distinct.
    *   **App Name:** Caravan Field Recorder
    *   **Database/Standard Name:** Caravan Corridors
    *   **File Format:** `.db` (SQLite)

## 2. Technical Capabilities
*   **CIDOC CRM Compliance:**
    *   **Answer:** **Aspirational.** There is no code implementing RDF, XML exports, or strict CIDOC ontologies.
    *   **Correction:** Change copy to "Designed with archaeological standards in mind" or "Standardized Vocabulary". Do not claim full CIDOC CRM compliance yet.

*   **Spatial Data (GIS):**
    *   **PostGIS Ready:** **No.** The app uses local SQLite (`better-sqlite3`). There is no PostGIS backend.
    *   **Visualization:** **Yes.** The app uses `Leaflet` and `React-Leaflet` for in-app map visualization.

*   **Customization:**
    *   **Answer:** **Yes.** Users can add custom columns to the `artifacts` table via the UI.

## 3. Data Integrity & Sync
*   **Relational Strictness:**
    *   **Answer:** **Loose.** SQLite is used but strict foreign key constraints are not enforced at the DB level for all relationships.
*   **Offline Sync:**
    *   **Answer:** **File-Based Check-in/Check-out.** The sync architecture (currently disabled/WIP) is designed to upload/download distinct `.db` files to cloud storage. It is not a real-time bi-directional record sync.

## 4. Visuals & Assets
*   **Screenshots:** None available in the repo.
*   **Logo:** None available (only default Electron/Vite icons).
*   **Action:** The landing page agent should generate mockups.

## 5. Target Audience
*   **Answer:** **Academic Research.** Fields like "Director", "Grid Square", and "Context" point to systematic academic excavation rather than commercial monitoring.
