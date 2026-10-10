ROADGUARD 🚧

Know the road before you reach it.
ROADGUARD is a community-powered road hazard reporting and awareness concept created for Hackoverflow 10.0 — Idea Submission. 
It aims to help road users report local hazards, make hazard information easier to review, and support a clearer path from report to resolution.

Current status: Front-end demo / MVP concept. 

The current version uses illustrative sample data and browser-local storage. 
It is not connected to a live road-authority system or a shared production database.

Table of Contents

- Problem
- Proposed Solution
- Features
- Demo Workflow
- Technology
- Run Locally
- Deploy
- Project Structure
- Roadmap
- Safety, Privacy, and Limitations


🚨 Problem

Road users can encounter potholes, waterlogging, debris, broken streetlights, damaged signals, and unsafe roadwork with little warning. 
Information about local hazards may be scattered across messages, calls, and word of mouth.
ROADGUARD explores a simple way to collect location-aware reports, help people review their freshness and status, 
and make the resolution process more visible.


💡 Proposed Solution

ROADGUARD is designed around one workflow:

Report → Verify → Alert → Resolve

1. Report: Submit a hazard category, location or landmark, optional coordinates, and a short description.
2. 
3. Verify: Review the report and, in a future connected version, use freshness and corroborating reports to support confidence.
4. 
5. Alert: A future backend can provide relevant proximity warnings, designed to avoid distracting people who are driving.
6. 
7. Resolve: Track whether a hazard is new, corroborated, acknowledged, or resolved.


 ✨ Features in the Current Demo
 
- Responsive dark navy and cyan interface.
- Dashboard cards showing total reports, reports needing attention, high-severity reports, and resolved reports.
- Interactive map using Leaflet and OpenStreetMap tiles (requires an internet connection).
- Sample hazard markers around Kanpur for demonstration only.
- Hazard report form with category, severity, landmark, optional latitude/longitude, and description.
- Browser geolocation button (requires permission and a secure context such as HTTPS or localhost).
- Report filters for all reports, reports needing attention, high-severity reports, and resolved reports.
- Demo status actions to corroborate, resolve, and reopen reports.
- Demo report data saved in the current browser using localStorage.


🧪 Demo Workflow

1. Open the dashboard and review the sample reports.
2. Use Report a hazard to add a demo report.
3. Enter a landmark and optionally provide both latitude and longitude.
4. Submit the report and view it in the dashboard.
5. Use Corroborate or Resolve to demonstrate the report lifecycle.
6. Use the filters to view reports by status or severity.
7. Select Reset demo data to restore the sample reports.


🛠 Technology Stack

Technology	                 Purpose
HTML5	                     Page structure
CSS3	                    Responsive layout and visual design
Vanilla JavaScript	      Form handling, filtering, status updates, and demo logic
Leaflet	                 Interactive map
OpenStreetMap         	 Map tiles and map data attribution
Browser localStorage  	 Saving demo reports in the current browser
Browser Geolocation API 	Optional location capture


💻 Run Locally

Option 1: Open the HTML file
1. Download or clone this repository.
2. Open index.html in a modern browser.
3. Keep an internet connection available for the map library and map tiles.
   

📁 Project Structure

roadguard/

├── index.html     # Responsive interactive front-end demo

└── README.md      # Project overview and setup instructions


🛡 Safety, Privacy, and Limitations

- This project is a demonstration and is not an emergency service or an official traffic information source.
- Sample map locations and reports are illustrative. Verify road conditions independently.
- Do not use the interface while driving. Submit reports only when safely stopped or as a passenger.
- Browser geolocation is optional and requires user permission.
- Demo reports are stored in browser-local storage and are not shared across devices or users.
- Do not enter sensitive personal information into demo reports.
- The demo does not verify hazards, guarantee safety, or demonstrate measured crash reduction or AI accuracy.
- A production release would require a backend, security and privacy review, moderation, operational monitoring, and coordination with relevant authorities.

👥 Team

Hackoverflow 10.0 — Idea Submission

Theme: Road Safety

- Team Leader: Vikash Kasaudhan — B.Tech, 3rd Year, PSIT Kanpur
- Team Member: Tejasva Gupta — B.Tech, 3rd Year, PSIT Kanpur
