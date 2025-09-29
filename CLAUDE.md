# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains a static website for a Thai competitive programming preparation course (หลักสูตรเตรียมความพร้อมก่อนเข้าค่าย 1 สอวน. คอมพิวเตอร์). The website provides detailed curriculum information for a 2-day, 12-hour C++ programming course.

## Repository Structure

```
/
├── index.html          # Main landing page with course overview
├── day1.html          # Day 1 curriculum (6 hours - basics and setup)
├── day2.html          # Day 2 curriculum (6 hours - data structures)
├── tips.html          # Instructor tips and recommendations
├── styles.css         # Comprehensive CSS styling
├── .gitattributes     # Git line ending configuration
└── CLAUDE.md          # This file
```

## Development Setup

This is a static HTML/CSS website that can be:
- Opened directly in a web browser
- Served using any static web server
- Deployed to GitHub Pages, Netlify, or similar static hosting

### Local Development
No build process required. Simply open `index.html` in a web browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

## Content Structure

### Course Information
- **Duration**: 2 days, 12 hours total
- **Language**: Thai
- **Target**: Preparation for Thai National Olympiad in Informatics (สอวน. คอมพิวเตอร์)
- **Programming Language**: C++
- **Tools**: Visual Studio Code + MinGW/g++

### Page Content
1. **index.html**: Course overview, goals, and navigation
2. **day1.html**: Detailed schedule for Day 1 (setup, basics, control structures)
3. **day2.html**: Detailed schedule for Day 2 (data structures, debugging, problem solving)
4. **tips.html**: Instructor recommendations and preparation checklist

## Styling

The website uses a modern, professional design with:
- Responsive grid layouts
- Green gradient theme (#10b981 to #047857)
- Mobile-first responsive design
- Smooth transitions and hover effects
- Thai typography using Prompt font family

## Git Configuration

- Line ending normalization configured via `.gitattributes`
- Main branch: `main`

## Deployment

This static site is ready for deployment to:
- GitHub Pages (recommended)
- Netlify
- Vercel
- Any static hosting service