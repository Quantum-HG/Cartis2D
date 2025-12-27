<style>
  body {
    background-color: #0d1117;
    color: #e6edf3;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
    line-height: 1.6;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }
  h1 {
    color: #58a6ff;
    font-size: 3em;
    text-align: center;
    margin-bottom: 0.5em;
    background: linear-gradient(135deg, #58a6ff 0%, #a371f7 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
  h2 {
    color: #58a6ff;
    border-bottom: 2px solid #58a6ff;
    padding-bottom: 0.3em;
    margin-top: 2em;
  }
  p, li {
    color: #8b949e;
  }
  strong {
    color: #e6edf3;
  }
  a {
    color: #58a6ff;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  code {
    background-color: #161b22;
    color: #e6edf3;
    padding: 2px 6px;
    border-radius: 3px;
  }
  blockquote {
    border-left: 4px solid #58a6ff;
    background-color: #161b22;
    padding: 1em;
    margin: 1em 0;
  }
  hr {
    border: none;
    border-top: 1px solid #30363d;
    margin: 2em 0;
  }
  @media (max-width: 768px) {
    body { padding: 15px; font-size: 16px; }
    h1 { font-size: 2em; }
    h2 { font-size: 1.5em; }
  }
  @media (max-width: 480px) {
    body { padding: 10px; font-size: 14px; }
    h1 { font-size: 1.75em; }
    h2 { font-size: 1.25em; }
  }
</style>

# Cartis2D

**A lightweight 2D level editor built for clarity, speed, and control.**

Cartis2D is a desktop level editor designed to make 2D map creation simple and predictable.  
It focuses on the essentials—tiles, objects, and layout—without unnecessary complexity.

<!-- Screenshot / GIF placeholder -->
<!-- Add main editor preview here -->

---

## What is Cartis2D?

Cartis2D is a standalone level editor for 2D games.

The editor is distributed as a pre-built desktop application and is **always free to use**.

While the editor itself is closed source, the **Python interface used to load Cartis2D maps in Pygame projects is open source**, ensuring transparency, flexibility, and easy integration.

---

## Why Cartis2D exists

Many level editors are powerful but heavy.  
For rapid iteration and focused workflows, this often becomes friction rather than help.

Cartis2D follows a different philosophy:

- Do less, but do it well  
- Prioritize speed and clarity  
- Avoid forcing everything onto a grid  
- Let developers focus on gameplay, not tooling  

---

## Core Features

- Tile-based level editing  
- Auto-tiling for corners, edges, and centers  
- Randomized tile placement from selected tile sets  
- Object system with position and size (not grid-locked)  
- Optional snap-to-grid for precise alignment  
- Lightweight UI designed for fast iteration  

<!-- Feature GIFs can be added here later -->

---

## Objects, not just tiles

Cartis2D treats **objects** as first-class elements.

An object is defined by **position and size**, making it suitable for:

- Enemy spawn points  
- Player start positions  
- Triggers and zones  
- 2D physics rectangles  
- Any dynamic game entity  

Objects can be freely placed or snapped to the grid depending on your needs.

<!-- Object system demo placeholder -->

---

## Platform & Availability

- Platform: Windows  
- Distribution: Installer via GitHub Releases  
- Cost: **Always Free**  
- Status: Actively developed  

---

## Python Integration (Open Source)

Cartis2D maps are loaded into games using a Python interface designed specifically for Pygame projects.

This interface is:
- Open source  
- Documented  
- Easy to integrate and extend  

<!-- Link to Python interface repo goes here -->

---

## Download

The latest version of Cartis2D is available via GitHub Releases.

**Download Cartis2D →**  
<!-- Link to latest release -->

---

## Development Philosophy

Cartis2D is built with a strong emphasis on:
- Finishing features instead of endlessly expanding scope  
- Predictable behavior over hidden complexity  
- Practical workflows over theoretical completeness  

Updates focus on polish, usability, and stability rather than feature bloat.

---

## License

Cartis2D is **free to use**.

- The editor is distributed as proprietary software  
- The Python integration interface is open source  

---

*Cartis2D is actively evolving. Feedback and real-world use cases help guide its direction.*
