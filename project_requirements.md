Create a modern production-ready responsive dashboard website using ONLY TWO FILES:

1. `index.html`
2. `config.json`

Website title:

# Vivo India ATC

Requirements:

1. `index.html`

* Must contain:

  * HTML
  * CSS
  * JavaScript
* DO NOT create:

  * style.css
  * script.js

2. `config.json`

* Store all categories and links inside JSON.
* Website must dynamically load data using:

```javascript
fetch('config.json')
```

3. UI Requirements:

* Modern dashboard design
* Dark premium glassmorphism theme
* Responsive mobile-friendly layout
* Smooth hover animations
* Sticky animated header
* Search/filter bar
* Category cards
* Collapsible categories
* Font Awesome icons
* Beautiful gradients
* Soft shadows
* Card animations
* Clean typography

4. Functional Requirements:

* Dynamically generate all sections from `config.json`
* Clicking a link must open in NEW TAB:

```javascript
window.open(url, "_blank");
```

5. Each category section should include:

* Category icon
* Category title
* Total link count
* Open all links button
* Collapse/expand button

6. Each link card should contain:

* Link title
* Open button
* Copy link button
* External link icon

7. Add these extra features:

* Recent opened links using localStorage
* Toast notification system
* Copy link functionality
* Search links instantly
* Footer with current year and last updated time
* Scroll-to-top button
* Mobile responsive hamburger menu

8. Use:

* Font Awesome CDN
* Modern semantic HTML5
* CSS variables
* Vanilla JavaScript only

9. JSON Structure should be EXACTLY like this:

```json id="3fc88b"
{
  "title": "Vivo India ATC",
  "categories": [
    {
      "name": "Task Reports",
      "icon": "fa-chart-line",
      "links": [
        {
          "title": "Main Project Task Timeline",
          "url": "https://docs.vivo.xyz/detail/office/020101665023?sheetIndex=2"
        },
        {
          "title": "Man Power",
          "url": "https://docs.vivo.xyz/i/sLWZZYj4V9lr0EImlpRlAE6qpVzw5jC_5ursAA5Y-_g?sheetIndex=2"
        },
        {
          "title": "Daily Project Status",
          "url": "https://docs.vivo.xyz/detail/office/020104105009?sheetIndex=3"
        },
        {
          "title": "China Daily Report Status",
          "url": "https://docs.vivo.xyz/detail/office/020108645839?sheetIndex=7"
        },
        {
          "title": "Manpower Status",
          "url": "https://docs.vivo.xyz/i/sLWZZYj4V9lr0EImlpRlAE6qpVzw5jC_5ursAA5Y-_g?sheetIndex=2"
        },
        {
          "title": "India Task Management Sheet (Always Update Henry)",
          "url": "https://docs.vivo.xyz/detail/office/020104105009?sheetIndex=3"
        },
        {
          "title": "Daily Report",
          "url": "https://docs.vivo.xyz/i/DFg1C7p7TAD9MTo2w9s208DMkOG-pwaoX3LbLUE8IOw?sheetIndex=9"
        }
      ]
    },
    {
      "name": "Feedback Links",
      "icon": "fa-comments",
      "links": [
        {
          "title": "Regular Feedback Link",
          "url": "https://docs.vivo.xyz/i/U-CpD_OUVW4D2uDoBqZiI5pqGOblcfOZlzBia-QSS9I?sheetIndex=3"
        }
      ]
    },
    {
      "name": "Tools",
      "icon": "fa-tools",
      "links": [
        {
          "title": "Log Extraction Link",
          "url": "https://ex-onelogmng-asia.vmic.xyz/admin/file-metadata/file-metadata"
        },
        {
          "title": "Bug Meat India",
          "url": "https://meat-in.vivo.com/project/bug?projectId=1080&issueTypeId=10482"
        },
        {
          "title": "Project Test Cases Assign",
          "url": "https://qcp-in.vivo.xyz/tot/subSheet?type=overseasSub&sheetId=432041"
        }
      ]
    },
    {
      "name": "My ATC Task Management",
      "icon": "fa-clipboard-list",
      "links": [
        {
          "title": "Create a New Sheet Document",
          "url": "https://docs.vivo.xyz/desktop/share/"
        },
        {
          "title": "Rahul Work My ATC",
          "url": "https://docs.vivo.xyz/detail/office/020114541556"
        },
        {
          "title": "ATC Project Weekly Project Status",
          "url": "https://docs.vivo.xyz/detail/office/020114518186"
        }
      ]
    }
  ]
}
```

10. Generate COMPLETE WORKING CODE for:

* `index.html`
* `config.json`

11. Code must be:

* production-ready
* modular
* clean
* well commented
* visually impressive

12. Add loading spinner while fetching JSON.

13. Add proper error handling if JSON fails to load.

14. Make the UI look premium like:

* modern admin dashboard
* developer portal
* enterprise internal tools page

15. Do not skip any implementation details.
