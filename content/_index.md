---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: Blue (1).jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 Professional Background'
      subtitle: ''
      text: 
       "Passionate about data engineering and analytics, I specialize in extracting, transforming, and analyzing data to drive informed decisions. With expertise in SQL, Python, Tableau, and statistical analysis, I have conducted SQL-based analysis on 10K+ grading records, identifying key performance trends that led to improvement in user engagement. By designing market research surveys and analyzing responses, I provided insights that optimized grading tools for over 80k students and 80+ universities"
    
"As a software engineer, I have worked extensively with C, C++, C#, Java, Python, and SQL to enhance security, optimize performance, and improve user experience. I strengthened system security by improving validation mechanisms and encrypting sensitive data, reducing unauthorized access risks across 40+ criteria. I upgraded the Mesa 3D Graphics Library, ensuring seamless performance for an interactive 3D Linux database application, and enhanced the User Manager GUI for MariaDB v10.5, improving data access management for 2.5M+ users.  "

"I’m seeking opportunities to apply my expertise in data engineering, analytics, and software development to create high-impact solutions. Whether it’s optimizing databases, leveraging data for business insights, or enhancing system security."
   
    design:
      columns: '1'
---
