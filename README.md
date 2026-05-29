# End-of-Term Report Comment Generator

![Version](https://img.shields.io/badge/version-1.1.0-blue)
![Platform](https://img.shields.io/badge/platform-GitHub%20Pages-brightgreen)
![LLM](https://img.shields.io/badge/Powered%20by-DeepSeek%20%7C%20Claude-blue)

An automated, web-based tool designed for Homeroom Teachers and ICT Teachers to generate professional, end-of-term student report comments in English. Built with a clean Lapis Lazuli interface, the tool streamlines the comment-writing process through structured attribute selection.

👉 **[Live Demo / Access the Tool](https://gaiasheep.github.io/End_of_Term_Report_Comment_Generator/)**

---

## Key Features

- **Dual-Role Mode**: Toggle between *Homeroom Teacher* and *ICT Teacher* to dynamically update core competencies and comment focus.
- **ICT Curriculum Alignment**: Integrated modules for high-frequency technical skills, including MS Word, MS Excel, Block Coding, Web Development, Python Programming, and MS Access.
- **Academic & Trend Integration**: Supports grading scales (A+ to D) and academic trends. Includes an **"N/A" (Not Applicable)** option as the default state for flexible scenario handling.
- **Custom Extensions (Others)**: Dedicated free-text input fields for both strengths and areas for improvement to capture unique student achievements.
- **Single-Paragraph Output**: The underlying prompt strictly constrains the LLM to output a single, continuous paragraph without any line breaks, bullet points, or numbering. Ideal for direct pasting into Notion databases or Excel cells.
- **Privacy & Local Storage**: Serverless architecture. Your API configuration is securely stored within your local browser's `localStorage` and is never transmitted to third parties.

---

## Quick Start

### 1. Configure the API
1. Open the tool and expand the **API Configuration** section at the top.
2. Enter your **DeepSeek API Key** (or any OpenAI-compatible endpoint key).
3. Check the default Base URL and Model Name, then collapse the section. Your settings will be cached locally.

### 2. Input and Select Attributes
1. Define the student's name, gender (for accurate pronoun mapping: *He/She*), and preferred word limit (default: 100 words).
2. Select the corresponding grade, academic trend, and ICT modules if applicable.
3. Check the relevant behavioral and academic keywords. Append custom remarks in the `Others` fields if necessary.
4. Click **Generate Comment**.

### 3. Copy Output
Click the **Copy** button beneath the output field to copy the text directly to your clipboard.

---

## Tech Stack

- **Frontend**: HTML5, CSS3 (Flexbox & Grid Layout), Vanilla JavaScript (Zero third-party dependencies)
- **UI & Architecture**: UX wireframing and frontend scaffolding assisted by **Claude AI**
- **LLM Core**: High-efficiency natural language generation and contextual refinement driven by **DeepSeek-v4**
- **Hosting**: Deployed seamlessly via **GitHub Pages**

---

## Contact & Integration

For feedback, tag requests, or inquiries regarding the 200-student batch export iteration, please feel free to reach out.

- **Author**: Gaia Yang
- **Email**: [gaiayang.edu@gmail.com](mailto:gaiayang.edu@gmail.com)
- **Workspace**: Fully optimized for embedding directly into **Notion** via `/embed`

---

<p align="center">
  Crafted with code and care by Ms. Gaia Yang | Powered by Claude AI, DeepSeek & GitHub
</p>
