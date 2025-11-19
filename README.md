# CSCI-4406 Computer Networks

## Overview
This repository contains lab assignments, reports, and supplemental materials for the CSCI-4406 Computer Networks course. Each lab directory holds one or more PDF documents (report/instructions/results) produced for that assignment. An extra lab (`Lab 11 - Extra`) may contain enrichment or bonus work beyond the core curriculum.

## Repository Structure
```
Lab 1/               # PDF reports for Lab 1
Lab 2/               # PDF reports for Lab 2
Lab 3/               # PDF reports for Lab 3
Lab 4/               # PDF reports for Lab 4
Lab 5/               # PDF reports for Lab 5
Lab 6/               # PDF reports for Lab 6
Lab 7/               # PDF reports for Lab 7
Lab 8/               # PDF reports for Lab 8
Lab 9/               # PDF reports for Lab 9
Lab 10/              # PDF reports for Lab 10
Lab 11 - Extra/      # Optional / bonus / exploratory lab work
LICENSE              # License governing repository contents
README.md            # Project overview and contribution guidance
```

## Lab Conventions
- Each lab folder stores one or more PDF files. Typical naming patterns observed:
  - `JLudolf_Lab_<n>.pdf`
  - `CLab<n>_Joshua_Ludolf.pdf` or similar
- Prefer consistent, descriptive naming: `<LastName><FirstInitial>_Lab_<n>.pdf` or `<CourseCode>_Lab<n>_<FullName>.pdf`.
- If additional assets (code, packet captures, configs) are needed later, create a subfolder (e.g., `Lab 3/code/`) and reference it inside the PDF.

## Adding a New Lab
1. Create a new folder: `Lab <n>/` (match existing numbering and spacing; avoid leading zeros).
2. Place your finalized PDF report(s) inside the folder.
3. (Optional) Add a brief plain-text `README.md` within the lab folder if code or datasets accompany the report.
4. Update the root `README.md` to include a short description of the lab's focus (e.g., "Transport layer reliability analysis").
5. Commit and push:
   ```powershell
   git add "Lab <n>" README.md; git commit -m "Add Lab <n> report"; git push
   ```

## Suggested Lab Description Placeholders
Fill these in as you revisit each lab:
- Lab 1: Introduction to network models / OSI vs TCP/IP (adjust if different)
- Lab 2: Basic packet inspection / Wireshark fundamentals (adjust if different)
- Lab 3: (Add summary)
- Lab 4: (Add summary)
- Lab 5: (Add summary)
- Lab 6: (Add summary)
- Lab 7: (Add summary)
- Lab 8: (Add summary)
- Lab 9: (Add summary)
- Lab 10: (Add summary)
- Lab 11 - Extra: (Add summary)

## Recommended Tools & Environment
While current materials are PDF-only, future expansions may include:
- Packet capture tools: Wireshark, tcpdump
- Network simulation/emulation: Mininet, GNS3
- Scripting for analysis: Python (Scapy), PowerShell for automation
Add a `requirements.txt` or `environment.yml` if code-based labs are introduced.

## Contribution Guidelines
- Keep commit messages concise and meaningful.
- Do not commit large binary traces unless essential; consider compressing (`.zip`) or documenting reproduction steps instead.
- Respect academic integrity: do not add solutions intended to be private if the course is ongoing.

## License
See `LICENSE` for terms. Ensure any third-party resources added comply with the repository's license and attribution requirements.

## Future Enhancements (Optional)
- Per-lab sub-README files summarizing objectives and outcomes.
- Scripts to automate packet analysis and produce charts embedded in reports.
- A consolidated index table mapping labs to topics and artifacts.

---
Feel free to update this file as the course progresses.
