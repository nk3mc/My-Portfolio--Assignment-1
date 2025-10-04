# Portfolio – Gradients and Color Scheme

# Color Scheme 
I used the following palette (from Adobe Color):
- Sky: #0ea5e9
- Indigo: #6366f1
- Violet: #a78bfa
- Amber: #f59e0b
- Ink (text/nav base): #111827

These colors are written directly into my CSS file.

## Where I used linear gradients (Requirement b)
- Header (Home page): straight linear-gradient from left to right  
  CSS: 
  ```css
  header {
    background: linear-gradient(to right, #6366f1, #0ea5e9);
  }

### Responsive Design (No Flexbox)
I used a **fluid layout** with percentage widths and `display: inline-block` (no flexbox or grid).  
The site loads one shared stylesheet plus three viewport-specific stylesheets:

```html
<link rel="stylesheet" href="style.css">                       <!-- shared -->
<link rel="stylesheet" media="(max-width: 599px)" href="mobile.css">
<link rel="stylesheet" media="(min-width: 600px) and (max-width: 1023px)" href="tablet.css">
<link rel="stylesheet" media="(min-width: 1024px)" href="laptop.css">

Viewports I used and why 

- Mobile (max-width: 599px) — `mobile.css`
  I chose 599px as the cutoff for mobile because most modern smartphones fit under this width.  
  On small screens, I switched the design to a **single column layout** (project cards stretch to about 98% of the screen).  
  This keeps everything large enough to read comfortably, avoids squishing content together, and prevents the need for annoying horizontal scrolling.

- Tablet (600–1023px) — `tablet.css`
  Tablets sit right in the middle between phones and laptops, so this range made sense for them.  
  In this viewport, I moved to a **two-column layout** (cards take about 48% width each).  
  This makes better use of the extra screen space while still keeping text lines at a readable length so users don’t have to scan too far across the screen.

- Laptop/Desktop (min-width: 1024px) — `laptop.css`
  Laptops and larger desktops usually start at 1024px wide and go up from there.  
  For these bigger screens, I designed a **three-column layout** (cards are around 31% wide each).  
  This lets me take advantage of the wider screen real estate without making paragraphs stretch too wide, which helps keep the reading experience comfortable.


https://nk3mc.github.io/My-Portfolio--Assignment-1/ -MY WEBSITE LINK

https://github.com/nk3mc/My-Portfolio--Assignment-1 - REPOSITORY LINK



