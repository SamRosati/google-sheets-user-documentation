# Google Sheets User Documentation

**Authors:** Sam Rosati & Ky Thai

## About This Project

This repository contains a "How-to" guide for **Google Sheets**, designed for beginner users. The documentation aims to teach essential data organization, calculation, and formatting skills clearly and effectively.

Beyond serving as a standalone tutorial, this project demonstrates our proficiency in applying best practices for **technical instruction writing** and **creating content for the web**. We have structured the guide to be easily navigable, accessible, and readable, accommodating the ways modern web users consume information.

## Methods and Processes

To plan, build, and deploy this documentation, we utilized the following methods and technologies to get to the final product:

### 1. Markdown for Semantic Web Writing

We wrote the content entirely in **Markdown**, which allowed us to cleanly separate content from formatting while remaining focused on structure. Using Markdown demonstrates an understanding of structuring content for the web:

- **Heading Hierarchy (`#`, `##`, `###`)**: Creates scannable sections to allow users to quickly find the exact information they need.
- **Lists and Tables**: Replaces dense paragraphs with bulleted lists, numbered steps, and reference tables, drastically improving readability.
- **Code Blocks & Inline Formatting (`Monospace`)**: Accurately denotes UI elements, formulas (`=SUM(A1:A10)`), and keystrokes to prevent ambiguity and reduce user frustration.

### 2. MkDocs & Material for MkDocs

We used **MkDocs**, a static site generator, alongside the **Material for MkDocs** theme to transform our Markdown source files into a polished, professional web application. This approach models modern "Docs-as-Code" workflows.

- **Navigation (`mkdocs.yml`)**: We structured the guide intuitively into an *Introduction*, *Instructions (Tasks 1-4)*, *Glossary*, and *Troubleshooting*. This layered architecture helps users effectively chunk their learning experience.
- **Admonitions & Callouts**: By leveraging Markdown extensions provided by MkDocs, we added contextual `Tip` and `Caution` blocks. These draw attention to important steps and potential pitfalls without breaking the flow of the standard instruction steps.
- **Responsive Design**: The Material theme guarantees the documentation looks pristine and reads seamlessly on any device or viewport size, confirming our adherence to "writing for the web" best practices.

### 3. Version Control & Collaborative Workflow

As this is a paired assignment, we used **Git and GitHub** to manage version control and collaborative editing.

- Working via a unified repository allowed us to track changes, review revisions, and parallelize our work without overwriting each other's contributions.
- **Automated Deployment (CI/CD)**: The project is continuously deployed to **GitHub Pages** using GitHub Actions (`.github/workflows/deploy.yml`). This creates an automated, seamless pipeline moving directly from writing a local draft to publishing the final live instruction set.

## Understanding Key Instruction Concepts

In drafting the actual instructional content, we explicitly incorporated technical writing principles discussed in COMM 2116:

- **Audience Analysis**: Written specifically for users with zero prior spreadsheet experience. We omitted unneeded jargon, established an upfront Glossary, and built tasks from the ground up, starting with simple cells to more complicated commands.
- **Action-Oriented Language**: Giving crisp, direct imperatives (e.g., "Click **File** > **Share**") rather than passive, confusing suggestions.
- **Visual Aids**: Integrating screenshots closely paired with the specific text steps. By mapping out exactly where specific UI elements live, we reinforce the textual instructions visually.
- **Troubleshooting Orientation**: We anticipated common user errors and included a dedicated Troubleshooting Section to answer preemptive questions and encourage user independence.

## Conclusion

This project is a culmination of our skills in communicating standard technical procedures simply, while also selecting the optimal tools (Markdown, MkDocs, GitHub Pages) to deliver that communication effectively via the web. By prioritizing scannability, clarity, and structural logic, this documentation validates our readiness to create and maintain high-quality user instruction materials suited directly for modern reader behaviors.
