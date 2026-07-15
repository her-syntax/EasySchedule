# EasySchedule - Timetable Studio

Timetable Studio is a powerful, client-side tool built to help students take raw, messy course schedules and turn them into clean, personalized, and printable timetables.

## Features
- **Upload and Parse:** Supports PDF, DOCX, TXT, and CSV.
- **Drag-and-Drop:** Reposition sessions easily within the grid.
- **Fully Customizable:** Adjust colors, fonts, layout, and block styling.
- **Clash Detection:** Automatically highlights scheduling conflicts.
- **Clean PDF Export:** Generate a professional, sidebar-free PDF of your finalized schedule.
- **Data Persistence:** Your changes are automatically saved to your browser.

## How to use
1. **Upload:** Click the "Upload" zone in the sidebar to load your schedule file.
2. **Select Modules:** Choose which modules you want to display from the generated list.
3. **Configure:** Use the "Dimensions and Layout" panel to set your start/end times and row density.
4. **Style:** Visit the "Theme and Customization" panel to change fonts, colors, and borders.
5. **Edit:** Click on any session block to adjust its individual appearance or remove it from the view.
6. **Export:** Click "Download PDF" to save your result.

## Tech Stack
- **HTML5/CSS3:** Grid-based layout for the timetable.
- **JavaScript (Vanilla):** Logic for state management, file parsing, and interaction.
- **Bootstrap 5:** UI framework for the sidebar and controls.
- **PDF Generation:** Powered by `jsPDF` and `html2canvas`.
- **Parsing:** `pdf.js` for PDF reading and `mammoth.js` for DOCX conversion.

## Credits
Designed by **Amukelani P.**
