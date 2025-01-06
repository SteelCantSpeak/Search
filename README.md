# CS50 Web50 Assignment: Search Interface Documentation

## Overview

This is a simple web application designed as part of the CS50 Web50 course assignment. The project consists of three pages with a search interface, including basic search functionality, image search, and advanced search options. The user interface aims to mimic the simplicity of Google’s design while offering more advanced search features.

### Pages Overview

1. **Search Page**  
   The main search page allows users to enter a search query and view relevant results. This mimics Google’s search page.

2. **Images Page**  
   The image search page allows users to search for images related to their query, providing visual results similar to Google’s image search functionality.

3. **Advanced Page**  
   The advanced search page includes additional filters for refining search results, offering options such as `ALL`, `EXACT`, `ANY`, and `NONE`.

---

## Features and Functionalities

### 1. **Search Page** (index.html)
   - **Functionality**: Users can enter a search term, and the page will show results similar to a simple Google search.
   - **Aesthetic**: The page is designed to look minimalist, mimicking Google's layout, with a search bar in the center and a simple results page.

### 2. **Images Page** (images.html)
   - **Functionality**: After entering a query, users can view image-based results. This functionality mimics Google's image search feature.
   - **Aesthetic**: The page displays search results in a grid-like pattern of images for easy viewing.

### 3. **Advanced Page** (advance.html)
   - **Functionality**: Users can refine their search using advanced filters. Options include:
     - **ALL**: Search results that match all query terms.
     - **EXACT**: Results that exactly match the search term.
     - **ANY**: Results that match any of the search terms.
     - **NONE**: Results that exclude the search terms.
   - **Aesthetic**: This page is designed vertically, maintaining consistency with the overall aesthetic that mimics Google's clean and organized interface.

### 4. **Feeling Lucky Button**
   - **Functionality**: A "Feeling Lucky" button is provided that takes the user to the first result of the search query, similar to Google's "I'm Feeling Lucky" feature.
   - **Note**: This was meant to be on index.html, but due to a mixup, was installed on advance.html

---

## Checklist Completion

- **At least three pages**: The project consists of three distinct pages:
  - index.html
  - images.html
  - advance.html
- **Simple but advanced**: The design is intentionally simple but provides an advanced search option for refining results.
- **Vertical layout**: The advanced page uses a vertical layout to match the overall aesthetic.
- **"Feeling Lucky" button**: Provides a feature to quickly access the first result, in line with Google’s “I’m Feeling Lucky” feature.

---

## Styling and Aesthetic

The design follows a minimalist aesthetic to ensure that the interface is simple, intuitive, and clean, much like Google’s interface. The following key points are reflected in the CSS:

- **Centered Search Bar**: The search bar is placed at the center of the page to provide a clear and user-friendly experience.
- **Vertical Layout**: The advanced search page uses a vertical layout with radio buttons for filter options, ensuring consistency in design across the pages.
- **Responsive Design**: The pages are designed to be responsive, ensuring they look good on both desktop and mobile devices.
