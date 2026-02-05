---
title: 'Skills'
date: 2023-10-24
type: landing

design:
  spacing: '0'   # Remove extra spacing to allow full-screen background

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
      css_class: dark
      height: "100vh"           # Full viewport height
      background:
        color: black
        image:
          filename: "Blue (1).jpg"
          filters:
            brightness: 1.0
          size: cover           # Ensures the image covers entire section
          position: center
          parallax: false
      text_color: white
      padding: "0 2rem"         # Reduce padding to fit full screen
      overlay:
        enable: true
        color: black
        opacity: 0.5
---

