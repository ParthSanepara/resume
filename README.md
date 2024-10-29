## Resume and Cover Letter

This repository contains my resume and a template for generating cover letters, both built using LaTeX.

### Prerequisites

* **LaTeX Distribution:** Ensure you have a LaTeX distribution installed on your system (e.g., TeX Live, MiKTeX).

### Building Documents

1. **Build Resume:**
   ```bash
   pdflatex  -file-line-error -halt-on-error -interaction=nonstopmode -recorder  "Parth_Sanepara_Sr_Firmware_engineer.tex"
1. **Build CoverLetter:**
   ```bash
   pdflatex  -file-line-error -halt-on-error -interaction=nonstopmode -recorder  "Parth_Sanepara_CoverLetter.tex"