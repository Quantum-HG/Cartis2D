<style>
  body {
    background-color: #0d1117;
    color: #e6edf3;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
    line-height: 1.7;
    max-width: 1000px;
    margin: 0 auto;
    padding: 40px 20px;
  }
  h1 {
    font-size: 3.5em;
    text-align: center;
    margin: 0.5em 0;
    background: linear-gradient(135deg, #3fb950 0%, #7ee787 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    font-weight: 700;
  }
  h2 {
    color: #3fb950;
    border-bottom: 3px solid #26a641;
    padding-bottom: 0.4em;
    margin: 2.5em 0 1em;
    font-size: 1.8em;
  }
  h3 {
    color: #7ee787;
    margin: 1.5em 0 0.8em;
  }
  p {
    color: #8b949e;
    font-size: 1.05em;
    margin: 0.8em 0;
  }
  strong {
    color: #3fb950;
    font-weight: 600;
  }
  ul {
    padding-left: 1.5em;
  }
  li {
    color: #8b949e;
    margin: 0.5em 0;
    font-size: 1.05em;
  }
  li::marker {
    color: #3fb950;
  }
  a {
    color: #3fb950;
    text-decoration: none;
    border-bottom: 1px solid transparent;
    transition: border-color 0.2s;
  }
  a:hover {
    border-bottom-color: #3fb950;
  }
  blockquote {
    border-left: 4px solid #3fb950;
    background-color: #161b22;
    padding: 1.2em 1.5em;
    margin: 1.5em 0;
    border-radius: 6px;
  }
  blockquote p {
    margin: 0.4em 0;
  }
  hr {
    border: none;
    border-top: 1px solid #21262d;
    margin: 3em 0;
  }
  .badge {
    display: inline-block;
    background: linear-gradient(135deg, #26a641 0%, #3fb950 100%);
    color: #fff;
    padding: 0.3em 0.8em;
    border-radius: 20px;
    font-size: 0.9em;
    font-weight: 600;
    margin: 0.5em 0;
  }
  .subtitle {
    text-align: center;
    color: #8b949e;
    font-size: 1.2em;
    margin-bottom: 3em;
  }
  @media (max-width: 768px) {
    body { padding: 30px 15px; }
    h1 { font-size: 2.5em; }
    h2 { font-size: 1.5em; }
    p, li { font-size: 1em; }
  }
  @media (max-width: 480px) {
    body { padding: 20px 12px; }
    h1 { font-size: 2em; }
    h2 { font-size: 1.3em; }
    .subtitle { font-size: 1em; }
  }
</style>

# Cartis2D

<p class="subtitle"><strong>A lightweight 2D level editor built for clarity, speed, and control.</strong></p>

<p class="badge">Always Free</p> <p class="badge">Open Source Python API</p> <p class="badge">Windows</p>

<p align="center">
  <img src="images/Cartis2D.png" alt="Cartis2D Editor" style="max-width: 100%; height: auto; border-radius: 8px; margin: 2em 0; box-shadow: 0 8px 30px rgba(63, 185, 80, 0.3);">
</p>

---

## Overview

Cartis2D is a desktop level editor for 2D games that makes map creation simple and predictable. It focuses on the essentials—tiles, objects, and layout—without unnecessary complexity.

The editor is **free to use** and distributed as a pre-built application. While the editor is closed source, the **Python interface for Pygame integration is fully open source**.

---

## Philosophy

> **Do less, but do it well**

Many level editors are powerful but heavy—creating friction instead of helping. Cartis2D prioritizes speed, clarity, and practical workflows over feature bloat.

- Rapid iteration without unnecessary complexity
- Flexible placement—not everything locked to a grid
- Focus on gameplay, not fighting your tools
- Predictable behavior over hidden magic

---

## Features

### Tile System
- **Auto-tiling** for corners, edges, and centers
- **Randomized placement** from tile sets for natural variation
- Fast, intuitive tile-based editing

### Object System
**Objects** are first-class elements defined by **position and size**, perfect for:
- Enemy spawns & player start positions
- Triggers, zones, and boundaries
- 2D physics rectangles
- Any dynamic game entity

ObjPython Integration

Maps load into Pygame projects via an **open source Python interface**:

- Clean, documented API
- Easy to integrate and extend
- Transparent implementation

---

## Download

Get the latest version from **[GitHub Releases](#)**

**Platform:** Windows • **Cost:** Free • **Status:** Actively Developed

---

## Development Approach

Updates focus on:
- **Finishing** over endless scope expansion
- **Polish and stability** over feature bloat
- **Real-world feedback** guiding direction

---

*Cartis2D is actively evolving. Your feedback helps shape its future

Cartis2D is **free to use**.

- The editor is distributed as proprietary software  
- The Python integration interface is open source  

---

*Cartis2D is actively evolving. Feedback and real-world use cases help guide its direction.*
