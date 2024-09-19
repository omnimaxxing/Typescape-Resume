# TypeScape Resume: A LaTeX Resume Template

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Typography and Design Choices](#typography-and-design-choices)
- [Packages Used](#packages-used)
- [Customization](#customization)
- [Compilation Instructions](#compilation-instructions)
- [Contributing](#contributing)


## Overview

The goal of this resume template is to provide a professional and visually appealing document that stands out to recruiters and hiring managers. Great attention has been paid to typography, spacing, and layout to ensure that the resume is both easy to read and aesthetically pleasing.

## Features

- **Professional Design**: Utilizes a clean and modern layout with a focus on readability.
- **Optimized Spacing**: Carefully adjusted spacing to make the best use of space without overcrowding.
- **Clear Visual Hierarchy**: Employs typographic principles to guide the reader's eye through the content.
- **ATS Friendly**: Ensures compatibility with Applicant Tracking Systems by using standard fonts and proper encoding.
- **Custom Commands**: Defines custom LaTeX commands for easy modification and consistency.
- **Compact Margins**: Uses minimal margins suitable for electronic viewing while maintaining readability.

## Typography and Design Choices

- **Font Selection**: Uses `newtxtext` and `newtxmath` packages for a Times-like professional font, which is widely accepted in professional documents.
- **Section Headers**: Styled with small caps (`\scshape`) and less boldness to create a subtle yet distinct separation between sections.
- **Company Titles**: Emphasized with bold and slightly larger font size to draw attention to professional experiences.
- **Visual Hierarchy**: Establishes a clear typographic hierarchy with varying font sizes and styles for different elements (name, section headers, job titles, bullet points).
- **Spacing Ratios**: Adjusted spacing before and after section titles for a tight yet readable layout.
- **Margins**: Set to 0.35 inches (left), 0.3 inches (right), and 0.25 inches (top and bottom) to maximize content space while maintaining readability.
- **Color Usage**: Minimal use of color, with blue used only for the "Portfolio" link to draw subtle attention without distracting from the content.

## Packages Used

This resume template utilizes several LaTeX packages to enhance functionality and appearance:

- `latexsym`: Provides additional mathematical symbols.
- `fullpage`: Sets reasonable margins.
- `titlesec`: Allows customization of section titles.
- `marvosym`: Provides additional symbols.
- `xcolor`: Allows for color customization.
- `enumitem`: Customizes list environments.
- `hyperref`: Handles cross-referencing and hyperlinks.
- `fancyhdr`: Customizes headers and footers.
- `babel`: Manages language-specific typographical rules.
- `tabularx`: Provides tabular environments with adjustable widths.
- `glyphtounicode`: Improves PDF text extraction (important for ATS compliance).
- `newtxtext` and `newtxmath`: Provides Times-like text and math fonts.

## Customization

The resume is designed to be easily customizable:

- **Personal Information**: Update your name, contact information, and links in the header section.
- **Sections**: Modify or add sections as needed (e.g., Projects, Certifications).
- **Experience Entries**: Use the `\resumeSubheading` and `\resumeItem` commands to add or modify experiences.
- **Skills and Interests**: Update the Technical Skills and Additional Interests sections to reflect your own.

### Custom Commands

- `\resumeItem`: Formats individual bullet points.
- `\resumeSubheading`: Formats job entries with company name, dates, position, and location.
- `\resumeSubSubheading`: Can be used for roles within a company if needed.
- `\resumeProjectHeading`: Formats project entries.
- `\resumeSubItem`: Used for sub-items under a project or experience.

## Compilation Instructions

To compile the resume, you need a LaTeX distribution installed on your system (e.g., TeX Live, MiKTeX) and a text editor or LaTeX IDE (e.g., TeXstudio, Overleaf).

### Steps:

1. Clone the Repository:

   ```bash
   git clone https://github.com/omnimaxxing/TypeScape-Resume.git

2. Navigate to the Directory:

   ```bash
   cd your-resume-repo

3. Compile the LaTeX Document:

   ```bash
   pdflatex resume.tex

### Notes:

- **Font Installation**: Since standard fonts are used, you shouldn't need to install any additional fonts.
- **ATS Compliance**: Ensure that the compiled PDF preserves the text content (avoid converting text to images).

## Contributing

If you have suggestions for improvements or find any issues, feel free to open an issue or submit a pull request.

### Guidelines:

- **Consistency**: Maintain the established formatting and style guidelines.
- **Clarity**: Ensure that any changes enhance readability and professionalism.
- **Relevance**: Keep content relevant to the purpose of the resume.
