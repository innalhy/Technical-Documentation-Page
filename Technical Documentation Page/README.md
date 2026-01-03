## Build a Technical Documentation Page 

#### Tech Stack

- **HTML5**: For semantic structure and content organization.
- **CSS3**: Custom styling with Flexbox-like positioning, media queries for responsiveness, and visual enhancements (e.g., code blocks, tables).
- **Bootstrap 5.3.3**: Used via CDN for responsive grid system, utility classes, and components (e.g., note boxes).

#### Features

- **Fixed Sidebar Navigation**: A persistent left-hand navbar with smooth-scrolling links to all documentation sections. On larger screens, it remains fixed; on smaller screens, it collapses to the top.
- **Responsive Design**: 
  - Fully responsive layout using CSS media queries.
  - At ≤815px, the navbar moves to the top and becomes scrollable.
  - At ≤400px, additional adjustments for code blocks and padding ensure readability on mobile devices.
- **Clean, Readable Typography**: Uses 'Open Sans' fallback to Arial/Sans-serif, with comfortable line-height and font sizing.
- **Syntax Highlighting Style for Code**: Code snippets are displayed in padded, rounded, light-gray blocks with preserved whitespace for better readability.
- **Interactive Elements**: Hover effects on navigation links and smooth scrolling when clicking navbar items.
- **Table Styling**: Striped, bordered comparison table for Python vs C++ differences.
- **Bootstrap Components**: Utilizes Bootstrap's alert component for the note about dictionary ordering in Python.
- **Accessibility Considerations**: Semantic HTML (nav, main, section, header), proper heading hierarchy, and sufficient color contrast.
- **Content Coverage**: 9 well-structured sections introducing Python basics, including installation, comparison with C++, variables, data types (mislabelled but covers globals), dictionaries, and built-in math functions.

#### User Stories (Completion Status)

All required freeCodeCamp user stories for the "Build a Technical Documentation Page" project are met:

1. ✅ `#main-doc` with main content  
2. ✅ At least 5 `.main-section` elements (has 9)  
3. ✅ Each `.main-section` starts with a `<header>` describing the topic  
4. ✅ Each `.main-section` has an `id` matching its header text (spaces replaced with underscores)  
5. ✅ At least 10 `<p>` elements total across sections  
6. ✅ At least 5 `<code>` elements total  
7. ✅ At least 5 `<li>` items total  
8. ✅ `#navbar` present  
9. ✅ Navbar contains a `<header>` with topic description  
10. ✅ One `.nav-link` for each `.main-section`  
11. ✅ Navbar `<header>` appears before links  
12. ✅ `.nav-link` text matches corresponding section header  
13. ✅ Clicking `.nav-link` navigates to correct section (smooth scroll)  
14. ✅ On regular-sized devices, navbar is fixed on the left and always visible  
15. ✅ At least one media query used (multiple for responsive behavior)
