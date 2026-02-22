# Project Walkthrough: 2M Tech Solutions Website

## 1. Project Overview
This project is a modern, responsive landing page for **2M Tech Solutions**, an IT agency providing web development, cloud services, and custom software. The website is designed with a **clean, corporate light theme** to convey professionalism and reliability.

## 2. Technology Stack
- **Core**: HTML5, CSS3
- **Framework**: Bootstrap 5.3.0 (for grid and responsive utilities)
- **Icons**: FontAwesome 6.4.0
- **Fonts**: Google Fonts ('Inter')
- **Scripting**: Vanilla JavaScript (ES6+)

## 3. Design System
The design adheres to a premium, "Intelligent IT" aesthetic using a specific color palette and modern typography.

### Color Palette
- **Primary Blue**: `#00AEEF` (Used for branding, buttons, and accents)
- **Secondary Dark**: `#333333` (Used for headings)
- **Background Light**: `#ffffff` and `#f8f9fa` (Gray variation for section contrast)
- **Text**: `#212529` (Dark gray for readability)

### Typography
- **Font Family**: 'Inter', sans-serif.
- **Weights**: varying from 300 (light) to 800 (bold) for hierarchy.

### UI Components
- **Buttons**: Flat, rounded corners (5px) with subtle hover transforms.
- **Cards**: Clean white cards with top borders (in primary color) and premium styling (box-shadows on hover).
- **Navigation**: Fixed top navbar with a transparent-to-shadow transition on scroll.

## 4. Key Sections
The single-page application is divided into logical sections:

1.  **Header (Navbar)**
    - Fixed position.
    - Contains Logo and navigation links (Home, About, Services, Case Studies).
    - "Talk to Experts" CTA button.

2.  **Hero Section**
    - Split layout: value proposition text on the left, high-quality feature image on the right.
    - Primary CTA "Get Started" and secondary CTA "View Case Studies".

3.  **About Section**
    - Highlights company history (Since 2016) and "Global Delivery, Local Impact" motto.
    - Key selling points: Scalable Solutions, Enterprise Security.

4.  **Services**
    - Grid layout displaying 4 key services:
        - Web Development
        - Cloud Services
        - IT Consulting
        - Software Dev
    - Cards feature hover lift effects and icons.

5.  **Portfolio (Case Studies)**
    - Showcase of recent projects (Logistics ERP, E-Commerce, Healthcare CRM).
    - Each item has a background image, category badge, and brief description.
    - Includes an "Expertise" strip showing tech icons (React, Apple, Android, Mobile).

6.  **Why Us**
    - Blue background section emphasizing core values: Expert Team, Security, Customer Centric, On-Time Delivery.

7.  **Contact**
    - Clean contact form asking for Name, Email, and Message.
    - Centered layout for focus.

8.  **Footer**
    - Minimal dark footer with logo, links, and copyright info.

## 5. File Structure
- `index.html`: Main entry point containing all markup.
- `style.css`: Custom styles overriding Bootstrap and implementing the design system.
- `script.js`: Handling potential interactivity (smooth scroll, navbar scroll effects).
- `assets/`: Directory for images (logo, etc.).

## 6. How to Run
Since this is a static site:
1.  Simply open `index.html` in any modern web browser.
2.  For development, use a local server (e.g., Live Server in VS Code) to ensure assets load correctly.
