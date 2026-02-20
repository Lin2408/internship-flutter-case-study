# Internship Case Study – Flutter Mobile App (WildReport / WildGuide)

> **Note:** Source code is **not publicly available** due to company policy/NDA.  
> This repository provides **demo videos** and a **technical summary** of my contributions during my internship.

## Demo Videos
- Demo 1 – WildGuide: <https://drive.google.com/file/d/16BJrkWWnQICHlZTk5pekbiZ8XVZpzWP0/view?usp=drive_link>
- Demo 2 – WildReport: <https://drive.google.com/file/d/1mn0mK9uUipVnGuxzDVWCAn7-Ui5DPS-K/view?usp=drive_lin)>

## Context
During my internship semester, I worked on improving a Flutter/Dart mobile application used for wildlife monitoring and reporting. The goal was to improve **user experience**, **feature completeness**, and **release readiness** based on testing results and stakeholder feedback.

## My Role
**Software Development Intern (Flutter/Dart)**  
Main responsibilities:
- Bug fixing and feature extension in the Flutter codebase
- Improving reliability (API usage, caching decisions, error handling)
- Testing (unit/widget tests + internal user tests)
- Release readiness (APK delivery, app size optimization, store compliance checklist)
- Collaboration with UI/UX designer and stakeholders

## Tech Stack / Tools
- Flutter / Dart
- REST API integrations
- GitHub workflow (issues, branches, PRs, reviews)
- VS Code, Android Emulator + physical devices
- Internal testing with paper test cases and weekly APK builds

## Key Contributions (Selected)
### 1) Map & Location Features
- Improved map interaction (smooth pan/zoom, draggable map)
- “Center on Me” reliably recenters to user location
- Enhanced markers (species/age display, tappable pins)
- Implemented map scale bar
- Implemented location tracking history visualization (polyline + timestamps)
- Fixed Android **release-build-only** map display issue

### 2) Reporting Flow Improvements
- Enabled selecting a location on the map when creating a report (not only current location)
- Improved list consistency and filtering behavior for animal reporting flows
- Fixed issues in damage report flow (validation and expected input behavior)
- Completed/implemented missing flows (e.g., logout, accident reporting where applicable)
- Improved confirmation messages and navigation logic to reduce user confusion

### 3) Reliability & Code Quality
- Implemented session persistence across app restarts with safe fallback on token expiry
- Improved validation and error messaging across reporting flows
- Refactoring for clearer separation of concerns (UI vs logic/services), reduced duplication
- Standardized commit/branch conventions and improved traceability (issues ↔ PRs)

### 4) Performance / Optimization
- Reduced Android release APK size from **>150MB to ~70MB** by enabling resource shrinking and cleaning up assets
- Improved logbook readability by showing human-friendly nearest city names (local dataset, no external API calls)

### 5) Testing & Evaluation
- Set up and maintained a fast test/debug loop (hot reload/restart, device verification)
- Conducted internal user tests with stakeholders using paper test cases (two rounds, improved results)
- Performed offline tracking storage capacity/performance tests
- Set up mock location to reliably test geo-related features
- Documented testing approach and results

### 6) Release Readiness & Handover
- Prepared store submission/compliance checklist (permissions, privacy policy, data safety, account deletion URL)
- Delivered weekly APK builds and changelogs for internal testing
- Produced handover/advisor summary with delivered features, technical decisions, and next steps

## Evidence (Optional)
- Testing Report (sanitized): ./docs/<file>.pdf
- Store Deployment Requirements (sanitized): ./docs/<file>.pdf
- Handover / Advisor Summary (sanitized): ./docs/<file>.pdf
- Screenshots / diagrams: ./assets/

## What I Can’t Share
- Full source code repository
- Internal documentation and sensitive data (accounts, endpoints, user data)

## Contact
Dexian Lin  
GitHub: https://github.com/Lin2408
