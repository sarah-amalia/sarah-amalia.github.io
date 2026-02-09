---
title: 'User Guide - CourseCorrect'
date: 2026-01-07T08:44:40+07:00
draft: false
slug: coursercorrect-user-guide
description: "Comprehensive end-user documentation for CourseCorrect, an AI-powered course discovery platform"
summary: "Independent user guide covering account setup, features, workflows, troubleshooting, and FAQ for CourseCorrect platform"
featured: false
tags:
  - end-user documentation
  - user guide
  - technical writing
  - saas 
categories:
  - projects
cover: "/images/user-guide-coursecorrect.png"
# Project-specific fields
github: "https://github.com/sarah-techwriter/coursecorrect-user-guide"
demo: "https://sarah-techwriter.github.io/coursecorrect-user-guide/"
website: "https://sarah-techwriter.github.io/coursecorrect-user-guide/"
tech_stack:
  - MKDocs
  - GitHub Pages
  - Stackedit
status: "completed"  # Options: completed, in_progress, planning
---

## Project Overview

This is a comprehensive, independently created user guide for CourseCorrect, an AI-powered course discovery platform that helps learners find the right online courses for their career goals. The documentation was created to demonstrate technical writing skills for a real-world SaaS product.

CourseCorrect uses AI (Cora) to match users with courses from over 150,000 options across platforms like Udemy, Coursera, and EdX. This guide provides complete documentation for both new users requiring initial setup guidance and existing users accessing advanced platform features.

The guide follows industry best practices for end-user documentation, with clear navigation, task-based workflows, visual aids, and comprehensive troubleshooting guidance. It demonstrates the ability to create documentation for diverse user types and skill levels.

**Disclaimer:** This is an independent documentation project not officially endorsed by CourseCorrect. Information is based on user experience and platform observation.


## Features

- Clear, structured documentation covering 8 major sections (60+ pages)
- Step-by-step account setup and getting started guide
- Comprehensive feature documentation with visual examples
- Task-based user workflows for common scenarios (career exploration, AI-guided learning, skill development)
- Detailed troubleshooting tables with symptoms, causes, and solutions
- Extensive FAQ section covering general, technical, privacy, and pricing questions
- System requirements and browser compatibility information
- Multiple support channels and self-service options

## Technologies Used

- **MkDocs** - Static site generator for documentation
- **GitHub Pages** - Free hosting platform for static sites
- **GitHub Actions** - Automated build and deployment pipeline
- **Markdown** - Lightweight markup language for content authoring
- **Visual Studio Code** - Content authoring and file management
- **YAML** - Configuration files for MkDocs and GitHub Actions
## Architecture

- Documentation built using MkDocs, converting Markdown content into static HTML
- Content organized in progressive disclosure structure (introduction → features → workflows → troubleshooting)
- Images stored in `docs/images/` directory with relative path references
- Automated deployment via GitHub Actions workflow
- Site deployed on GitHub Pages infrastructure without server-side dependencies
- Follows docs-as-code workflow with version control via GitHub
- Table of contents auto-generated from Markdown headings for easy navigation


## Screenshots

![](/images/user-guide-coursecorrect.png)
## Challenges and Solutions

**Challenge: Documenting a third-party platform without official access**  
Creating comprehensive documentation for a platform I don't own or have inside knowledge of required careful observation and user testing.

**Solution:** Systematically explored every feature and workflow as an actual user, documenting step-by-step processes with screenshots. Tested all features multiple times to ensure accuracy. Included a disclaimer noting this is an independent guide based on user experience.

---

**Challenge: Organizing extensive content for multiple user types**  
The platform serves diverse users (career changers, students, professionals) with different needs and technical skill levels.

**Solution:** Implemented progressive disclosure structure: quick start for beginners, detailed feature documentation for regular users, and advanced workflows for power users. Created task-based workflows showing how different user types accomplish their specific goals.

---

**Challenge: Making troubleshooting information easily scannable**  
Users in troubleshooting mode need quick answers without reading paragraphs of text.

**Solution:** Created structured troubleshooting tables with four columns: Problem, Symptoms, Possible Causes, and Solutions. This format allows users to quickly identify their issue and find the solution. Added "Prevention" tips to help users avoid future problems.

---

**Challenge: Setting up automated documentation deployment**  
GitHub Pages and MkDocs required specific configuration for automated builds.

**Solution:** Configured GitHub Actions workflow (`.github/workflows/ci.yml`) to automatically build and deploy documentation on every commit. Set up proper branch structure with `main` for source files and `gh-pages` for deployed site. This creates a maintainable docs-as-code workflow.

---

**Challenge: Keeping documentation maintainable as platform evolves**  
CourseCorrect updates regularly, which could make documentation outdated.

**Solution:** Used descriptive language focused on concepts rather than exact UI text. Included version information and "last updated" dates. Structured content modularly so individual sections can be updated independently. Added note about information being based on user experience and potentially becoming outdated.

## Future Improvements

This project is considered complete as a demonstration of information architecture and content structuring skills.

But, if any change needed to improve this project, I may:  
- Add video tutorials for complex workflows
- Create interactive demos or GIFs showing feature usage
- Expand workflow examples with more user scenarios
- Add comparison tables between CourseCorrect and competitor platforms
- Include glossary of AI/course discovery terminology
- Create quick reference cards for common tasks
- Add accessibility documentation (screen reader support, keyboard shortcuts)
- Implement search functionality for easier navigation
- Create printable PDF version of the guide
