# BALANCE Chemistry — Monitoring & Developer Portal
**Enterprise Multi-Campus Telemetry, Student Analytics & Operational Triage**

Independent developer and operations monitoring portal for the **BALANCE Chemistry** platform across four international school campuses:
- **BISC** (British International School in Cairo)
- **BHS** (Brummana High School)
- **NIS** (Dr. Nermien Ismail Schools)
- **GPIS** (Green Land International School)

---

## 🌐 Live Access Links

- **Live GitHub Pages Portal**: [https://protoobooluka2-eng.github.io/BALANCE-Developer-Portal/](https://protoobooluka2-eng.github.io/BALANCE-Developer-Portal/)
- **Direct Portal Route**: [https://protoobooluka2-eng.github.io/BALANCE-Developer-Portal/DEVELOPER_PORTAL.html](https://protoobooluka2-eng.github.io/BALANCE-Developer-Portal/DEVELOPER_PORTAL.html)

---

## 🔑 Access Credentials
Access to the Developer Portal requires platform authentication. Valid keys:
- `tok_dev`
- `balance2026`

---

## 🏛️ Information Architecture & Navigation Hierarchy

```
Developer Portal (Campus Hub)
  ├── 1. BISC (British International School in Cairo)
  ├── 2. BHS (Brummana High School)
  ├── 3. NIS (Dr. Nermien Ismail Schools)
  └── 4. GPIS (Green Land International School)
        │
        ├── [STUDENTS] ──► Search & Class Filter Table ──► Individual Student Profile
        │                                                    ├── 9-Lab Curriculum Progress
        │                                                    ├── Diagnostic Struggle Analysis
        │                                                    └── Chronological Recorded Sessions
        │                                                          └── Detailed Session Telemetry
        │                                                                ├── A. Activity Timeline
        │                                                                ├── B. Lab-by-Lab Metrics
        │                                                                ├── C. Action Telemetry
        │                                                                ├── D. 4-Level Question Breakdown
        │                                                                ├── E. Challenge Case Performance
        │                                                                └── F. Stage Progression
        │
        ├── [TEACHERS] ──► Faculty Profiles ──► Assigned Classes ──► Read-Only Student Progress Rosters
        │                                    └── Teacher Inquiries & Scientific Reports
        │
        ├── [PARENTS]  ──► Guardian Profiles ──► Linked Student Cards ──► Direct Student Navigation
        │                                    └── Pedagogical Questions & Inquiries
        │
        └── [TICKETS]  ──► Feedback Triage Feed & Developer Resolution Notes
```

---

## 🎨 Monochrome Design System
Strict professional black, white, charcoal, and light-gray palette designed for high-density enterprise data presentation without bright brand distractions.

---

## 🔒 Privacy & Compliance
- Student IP addresses are masked by default (`82.129.***.***`).
- Real-time GPS or device coordinates are strictly disabled.
- In production telemetry mode, uncaptured client metrics are visibly marked as `Not recorded`.
