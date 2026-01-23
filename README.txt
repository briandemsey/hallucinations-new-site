HALLUCINATIONS.CLOUD - WEBSITE CONTENT FILES
=============================================
Created: January 22, 2026

FOLDER CONTENTS
---------------
pages/
  01-homepage.html           - Main landing page
  02-products.html           - Products & features page
  03-working-model.html      - Interactive demo page
  04-about.html              - About page with founder bio
  05-resources.html          - Reports, case studies, glossary
  06-insights-ai-in-context.html  - Industry blog
  07-insights-llm-real-life.html  - Brian's editorial blog
  08-contact.html            - Contact form and info


HOW TO USE THESE FILES
----------------------

OPTION 1: Preview Locally
- Double-click any .html file to open in your browser
- Each page is self-contained with embedded CSS
- Preview to see layout and content before importing

OPTION 2: Import to Webflow
1. Create a new Webflow project
2. For each page:
   - Create a new page in Webflow
   - Open the HTML file in a text editor
   - Copy section content into Webflow using their visual builder
   - Apply styles using Webflow's style panel
3. The CSS in each file serves as a reference for colors, spacing, fonts

OPTION 3: Use with Other Builders
- These files work with any platform that accepts HTML/CSS
- Copy/paste content sections as needed
- Adapt styling to your platform's capabilities


KEY DESIGN ELEMENTS
-------------------
Colors:
  Primary Dark:    #1a1a2e
  Secondary Dark:  #0f3460
  Accent Red:      #e94560
  Light Gray:      #f8f9fa
  Text Dark:       #1a1a2e
  Text Medium:     #555
  Text Light:      #888

Fonts:
  Headings: Segoe UI, system-ui, sans-serif
  Body: Segoe UI, system-ui, sans-serif
  LLM Real Life blog uses Georgia (serif) for editorial feel

Button Styles:
  Primary: Red (#e94560) with white text
  Secondary: Transparent with border


ITEMS TO REPLACE
----------------
Throughout the files, replace these placeholders:

1. Demsey - Replace with Brian's actual last name
2. [IMAGE] comments - Add actual images or graphics
3. [Streamlit URL] - Add your actual Streamlit app URL in working-model page
4. Email addresses - Verify these are correct
5. Social media links - Add actual profile URLs
6. Logo references - Add your logo file


SEO INCLUDED
------------
Each page includes:
- Meta title and description
- Meta keywords
- Schema.org JSON-LD markup for:
  - Organization
  - Person (Brian)
  - SoftwareApplication
  - Blog
  - ContactPage
  - FAQPage


NEXT STEPS
----------
1. Preview files in browser
2. Decide on final platform (Webflow recommended)
3. Replace placeholder content
4. Add actual images and graphics
5. Connect Streamlit app
6. Set up email handling for contact form
7. Configure newsletter signup integration
8. Add analytics tracking
9. Test on mobile devices
10. Launch!


NOTES
-----
- All pages are responsive (mobile-friendly)
- CSS is embedded for easy preview, but should be extracted
  into a single stylesheet for production
- Schema markup helps with SEO and AI answer engines
- The "Live Stats Bar" on contact page can be made dynamic
