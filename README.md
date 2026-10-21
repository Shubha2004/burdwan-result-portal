# Burdwan Result & Admit Card Search Portal

**The University of Burdwan — Department of Controller of Examinations**
Provisional Results of 4 Year Honours Programme under CCFUP in Bachelor of Arts, **Semester I Examination 2025**
**Tarakeswar Degree College — College Code: 415** (Badge Codes 207–210), integrated with B.A. Semester-II Examination 2026 admit-card profiles.

Live site: https://shubha2004.github.io/burdwan-result-portal/

## Features
- Instant search by student name (partial / full, case-insensitive), Roll No., or Registration No.
- Filters: Qualified (Q), Semester Not Qualified (SNC), With Admit Card Name, Admit Card Only; Major-subject filter built from the data
- Sort by Roll No., Name, or SGPA (All)
- Live summary dashboard: 164 result records — 117 Q, 47 SNC, 147 admit-card profiles linked
- Click any student for a printable provisional marksheet (Print / Save as PDF)
- Admin bulk name importer (saved in the browser via localStorage) and CSV export of the filtered list

## Data
- Results transcribed from the official provisional result sheets, Pages 1–4 (164 candidates as printed on Page 4)
- Names, guardians, registration numbers, gender, category and Major/Minor subjects from the Semester-II 2026 admit-card PDF (132 cards) plus supplementary supplied profiles
- 27 result rows have no matching admit card in the supplied documents and can be added through the portal's **+ Names** importer

Single-file static site (`index.html`, Tailwind CDN + vanilla JS). No backend.
