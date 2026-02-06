---
title: 'Skills'
date: 2023-10-24
type: landing

design:
  spacing: '10rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
      subtitle: "Technical Skills, Professional Skills, and Interests"
    
    design:
      show_skill_percentage: false   # cleaner, icon-focused layout
      css_class: dark
      padding_top: 80
      padding_bottom: 80
      background:
        color: "#0b0b0b"   # darker for contrast
        overlay:
          color: "#111111"
          opacity: 0.6
        image:
          filename: Blue (1).jpg
          filters:
            brightness: 0.7
          size: cover
          position: center
          parallax: true   # adds subtle movement
      title:
        color: "#facc15"  # amber/yellow accent
        uppercase: true
        font_weight: bold
        font_size: 48px
      subtitle:
        color: "#ffffff"
        font_size: 20px
        margin_top: 10
---
