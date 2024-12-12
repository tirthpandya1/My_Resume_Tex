# ATS-Friendly LaTeX Resume

This is an ATS-friendly LaTeX resume template that's designed to be both machine-readable and visually appealing.

## Requirements

To compile this resume, you'll need:
- A LaTeX distribution (TeX Live or MiKTeX)
- A PDF viewer
- (Optional) A LaTeX editor like TeXmaker, TeXstudio, or VS Code with LaTeX extension

## How to Compile

1. Using command line:
   ```bash
   pdflatex main.tex
   ```

2. Using an editor:
   - Open main.tex in your LaTeX editor
   - Click the "Build" or "Compile" button
   - The output will be main.pdf

## Structure

- `main.tex`: The main resume file
- Generated files:
  - `main.pdf`: The compiled resume
  - Various auxiliary files (`.aux`, `.log`, etc.)

## Editing Tips

1. Personal Information:
   - Update the header section with your details
   - Modify contact information and links

2. Sections:
   - Education
   - Experience
   - Skills
   - Projects

3. Formatting:
   - Use `\resumeItem` for bullet points
   - Use `\resumeSubheading` for job/education entries
   - Maintain consistent spacing

## ATS Optimization

This template is designed to be ATS-friendly by:
- Using standard section headings
- Avoiding complex formatting
- Using machine-readable fonts
- Maintaining a clean, simple structure

## Need Help?

For LaTeX help:
- [LaTeX Wikibook](https://en.wikibooks.org/wiki/LaTeX)
- [TeX StackExchange](https://tex.stackexchange.com/)
