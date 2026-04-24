# LSPD RevoRP - Website Specification

## Project Overview
- **Name**: LSPD RevoRP Webpage
- **Type**: Static informational website
- **Core Functionality**: Official page for Los Santos Police Department in RevoRP GTA V server
- **Target Users**: Players interested in joining LSPD, current members, visitors

## UI/UX Specification

### Layout Structure
- **Header**: Fixed navigation with logo and menu links
- **Hero Section**: Full-width banner with department name and tagline
- **Sections**: About, Commands, Rules, Application
- **Footer**: Copyright and social links

### Responsive Breakpoints
- Mobile: < 768px
- Desktop: >= 768px

### Visual Design

#### Color Palette
- **Primary**: #0A192F (dark navy blue - authority)
- **Secondary**: #1E3A5F (deep blue)
- **Accent**: #D4AF37 (gold - prestige)
- **Accent Light**: #FFD700 (bright gold)
- **Text Light**: #E8E8E8 (off-white)
- **Text Dark**: #1A1A1A (near black)
- **Warning**: #FF4444 (emergency red)
- **Background**: #0D1B2A (dark blue-black)

#### Typography
- **Headings**: "Orbitron", sans-serif (police/military feel)
- **Body**: "Rajdhani", sans-serif (modern, readable)
- **Hero Title**: 48px mobile, 72px desktop
- **Section Titles**: 32px mobile, 48px desktop
- **Body Text**: 16px mobile, 18px desktop

#### Visual Effects
- Gold accent borders on cards
- Subtle glow effect on buttons
- Smooth scroll behavior
- Hover animations on interactive elements

### Components

#### Navigation
- Logo (LSPD badge text)
- Menu: Inicio, Historia, Mando, Normas, Cómo Unirse
- Mobile hamburger menu

#### Hero Section
- Department name: "LOS SANTOS POLICE DEPARTMENT"
- Server name: "RevoRP"
- Tagline: "Protect & Serve"
- Call-to-action button

#### About Section
- Brief history of LSPD in RevoRP
- Mission statement

#### Commands/Jefatura Section
- Rank hierarchy with icons
- Current command staff

#### Rules Section
- Key rules for members
- Code of conduct

#### Application Section
- Requirements
- How to apply
- Contact information

#### Footer
- Copyright
- RevoRP server branding

## Functionality Specification

### Core Features
- Smooth scroll navigation
- Mobile responsive menu
- Hover effects on buttons and cards
- Animated section reveals

### User Interactions
- Click navigation links → smooth scroll to section
- Click hamburger → toggle mobile menu
- Hover buttons → visual feedback

## Acceptance Criteria
- [x] Page loads without errors
- [x] All sections visible and properly styled
- [x] Navigation works (smooth scroll)
- [x] Mobile menu toggles correctly
- [x] Responsive on mobile and desktop
- [x] Fonts load correctly
- [x] Gold accents visible on key elements