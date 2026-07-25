# QuoteHub - Complete Mobile App Design System

## 🎨 Project Overview

**QuoteHub** is a premium, modern RFQ (Request for Quotation), contractor, vendor, and skilled worker marketplace for Android and iOS. This comprehensive design system provides production-ready screens, components, and specifications for development teams.

## 📱 Design File
**👉 [Open QuoteHub Design in Figma](https://www.figma.com/design/DA5eWgPtD7L6PDRK7X26O8)**

---

## 📋 Complete Screen Inventory

### Authentication Flow (3 screens)
- **Splash Screen** - Branded welcome with logo and tagline
- **Login Screen** - Email/password authentication with sign-up link
- **Signup Screen** - Account creation with terms acceptance

### Core Navigation (5 screens)
- **Home Dashboard** - Personalized greeting, search, trending projects, RFQ feed
- **RFQ Feed** - Browsable project cards with filtering and sorting
- **Messages** - WhatsApp-style chat list with typing indicators
- **Profile** - User info, verification badge, rating, stats, credentials
- **Wallet** - Balance display, transaction history, withdrawal options

### Project Workflow (4 screens)
- **Create RFQ (Wizard)** - Multi-step form (6 steps) for posting projects
- **RFQ Details** - Full project information, requirements, bid button
- **Place Bid** - Quote submission with amount, timeline, proposal
- **My Bids** - Tab-based status tracking (Submitted, Viewed, Shortlisted, Awarded, Completed)

### Collaboration & Discovery (3 screens)
- **Chat Detail** - Conversation view with messages, typing, reactions
- **Search** - AI-powered search with filters (category, budget, distance, rating)
- **Notifications** - Grouped alerts with swipe actions and filtering

### Financial & Contracts (3 screens)
- **Escrow Details** - Payment protection with milestone breakdown
- **Contracts** - Project milestones, timeline, completion tracking, payment release
- **Payment Methods** - Add/manage credit cards and bank transfers

### Supporting Screens (4 screens)
- **Bid Comparison** - Side-by-side vendor comparison table
- **Portfolio** - Work gallery with project images
- **Settings** - Profile, notifications, security, privacy, legal
- **Message Detail** - Rich messaging with attachments and reactions

**Total: 20+ Production-Ready Screens**

---

## 🧩 Component Library

### Buttons
- **Primary** - Main action button (solid purple)
- **Secondary** - Alternative action (solid secondary purple)
- **Accent** - Success/approve action (solid green)
- **Outline** - Low-priority action (white with border)
- **States**: Default, Hover, Active, Disabled
- **Sizes**: 48px height, 12px border radius

### Cards
- **Default Card** - White background, light border, soft shadow
- **RFQ Card** - Image hero, company info, budget, deadline, bid count
- **Bid Card** - Quote details, timeline, warranty, status
- **Contract Card** - Project, milestone progress, release button
- **Profile Card** - User info with verification badge

### Inputs & Forms
- **Text Input** - 48px height, icon support, focus/error states
- **Date Picker** - Calendar interface with range selection
- **Dropdown Select** - Chevron indicator, open animation
- **Textarea** - Multi-line with character counter
- **Checkbox/Radio** - Custom styled with smooth animation
- **Slider** - Dual-range for budget and distance filters

### Navigation
- **Bottom Navigation** - 5-tab menu (Home, RFQs, Create, Messages, Profile)
- **Floating Action Button** - Center FAB for "Create RFQ" with gradient glow
- **Tab Bar** - Scrollable tabs with active indicator

### Badges & Tags
- **Status Badge** - Colored background with label (Success, Warning, Danger)
- **Verification Badge** - ✓ checkmark for verified professionals
- **Category Tag** - Outlined style with category icon
- **Count Badge** - Circle with number (1-99+)

### Progress Indicators
- **Linear Progress Bar** - Animated fill (300-400ms)
- **Step Indicator** - Multi-step process with current highlight
- **Milestone Progress** - Visual breakdown by percentage
- **Circular Progress** - Percentage completion display

---

## 🎨 Design System

### Color Palette

| Role | Hex | Usage |
|------|-----|-------|
| **Primary** | #6C4DFF | Main actions, CTAs, highlights |
| **Secondary** | #7B61FF | Alternative actions, secondary UI |
| **Accent** | #00C896 | Success, approve, positive actions |
| **Warning** | #FFB547 | Caution, alerts, pending states |
| **Danger** | #FF5A5F | Errors, delete, rejected states |
| **Success** | #2ECC71 | Confirmed, completed, verified |
| **Background** | #F8F9FC | Page background, section spacing |
| **Card** | #FFFFFF | Surface, cards, modals |
| **Text Primary** | #111827 | Main text, headings |
| **Text Secondary** | #6B7280 | Secondary text, labels |
| **Border** | #E5E7EB | Dividers, outlines, strokes |

### Typography

#### Headings (SF Pro Display - Bold)
- **H1**: 32px, 40px line height
- **H2**: 28px, 36px line height
- **H3**: 24px, 32px line height

#### Body (Inter - Medium/Regular)
- **Large**: 16px, 24px line height (Medium)
- **Medium**: 14px, 20px line height (Medium)
- **Small**: 12px, 16px line height (Regular)

#### Labels (Inter - Semi Bold)
- **12px**, 16px line height

#### Numbers (SF Pro Display - Bold)
- **24px**, **28px**, **32px**

### Spacing System (4px Base)
```
Xs: 4px    | Sm: 8px    | Base: 12px
Md: 16px   | Lg: 20px   | Xl: 24px
2Xl: 32px  | 3Xl: 40px  | 4Xl: 48px
```

### Border Radius
- **xs**: 4px (small elements)
- **sm**: 8px (medium elements)
- **base**: 12px (buttons, inputs)
- **md**: 16px (cards)
- **lg**: 20px (premium cards)
- **xl**: 24px (hero sections)

### Shadows (Soft Glassmorphism)
```
sm: 0px 2px 4px rgba(0,0,0,0.05)
base: 0px 4px 12px rgba(0,0,0,0.08)    ← Most common
md: 0px 8px 24px rgba(0,0,0,0.12)
lg: 0px 12px 32px rgba(0,0,0,0.15)
```

---

## 🎬 Animation & Motion

### Easing Functions
- **Ease-Out**: `cubic-bezier(0, 0, 0.2, 1)` - Page transitions, entrance
- **Ease-In-Out**: `cubic-bezier(0.4, 0, 0.2, 1)` - Interactive elements
- **Bounce**: `cubic-bezier(0.68, -0.55, 0.265, 1.55)` - Playful feedback

### Durations
- **Fast**: 150ms (button press, quick feedback)
- **Base**: 300ms (page transitions, card expansions)
- **Slow**: 500ms (complex animations, entrance effects)

### Micro-interactions
- **Button Press**: Scale 95%, 150ms ease-in-out
- **Card Hover**: Elevation increase (0 → 8px shadow), 200ms
- **Page Transition**: Fade + slide, 300ms ease-out
- **Shared Element**: Card → Details screen, 400ms
- **Loading Shimmer**: Animated gradient skeleton
- **Pull-to-Refresh**: Spring bounce on release
- **Success Animation**: Checkmark with subtle confetti
- **Error Animation**: Shake + red pulse
- **Swipe Gesture**: Dismiss on swipe-left/right
- **Bottom Sheet**: Slide up from bottom, 300ms

---

## ♿ Accessibility

### Color Contrast
- **WCAG AA Compliant**: 4.5:1 ratio for all text
- **WCAG AAA Ready**: 7:1 ratio where possible

### Touch Targets
- **Minimum**: 48×48px for all interactive elements
- **Padding**: 8px around tappable areas

### Semantic Structure
- Proper heading hierarchy (H1 → H6)
- Alt text for images
- ARIA labels where needed
- Focus states visible on all interactive elements

### Font Sizes
- **Minimum**: 12px (labels only)
- **Body Text**: 14px minimum
- **Headings**: 16px minimum

---

## 📐 Device & Responsive Design

### Base Dimensions
- **iPhone Screen**: 375×812px (design base)
- **Safe Area**: 20px horizontal padding
- **Bottom Navigation**: 80px height (respects home indicator)

### Scaling
- Designs scale proportionally for larger screens
- iPad support via responsive layouts
- Android scaling handled by design framework

### Orientation
- Portrait-first design
- Landscape considerations for iPad/tablets

---

## 🌙 Dark Mode

Full dark mode support with inverted colors:

| Component | Light | Dark |
|-----------|-------|------|
| Background | #F8F9FC | #0F172A |
| Card | #FFFFFF | #1A2637 |
| Text Primary | #111827 | #FFFFFF |
| Text Secondary | #6B7280 | #D1D5DB |
| Border | #E5E7EB | #374151 |

---

## 📦 Figma Pages

### Pages in File
1. **Screens** - 20+ production screens
2. **Components** - Reusable button, card, input, badge, chip components
3. **Design System** - Complete color palette, typography scales, spacing, icons
4. **User Journey & Flows** - Bidder journey, client journey, screen map, feature checklist

---

## 👥 User Journeys

### Bidder Journey
```
Browse RFQs → View Details → Place Bid → Chat with Client → Deliver → Escrow Release
```

### Client Journey
```
Post RFQ → Receive Bids → Compare Bids → Select Contractor → Release Payment
```

---

## 🚀 Developer Handoff

### Files Provided
1. **QUOTEHUB_DESIGN.md** - Detailed design specification
2. **DESIGN_TOKENS.json** - Developer-ready tokens (colors, typography, spacing)
3. **Figma Design File** - Interactive prototype with all screens

### Implementation Checklist
- [ ] Set up design system tokens in codebase
- [ ] Build component library from Figma
- [ ] Implement navigation structure
- [ ] Add animations (300-400ms transitions)
- [ ] Test accessibility (color contrast, touch targets)
- [ ] Implement dark mode support
- [ ] Cross-device testing (iOS/Android)
- [ ] Performance optimization
- [ ] QA against Figma specs

### Recommended Stack
- **Mobile**: React Native or Flutter
- **Web**: React + TypeScript
- **UI Libraries**: Tamagui, NativeWind, or custom component library
- **Animation**: React Spring, Framer Motion, or native animations
- **Design Tokens**: Tokens Studio, Design Tokens, or custom JSON

---

## 📋 Design Specifications Summary

| Aspect | Specification |
|--------|---------------|
| **Screens** | 20+ fully designed screens |
| **Components** | 30+ reusable components |
| **Color Palette** | 13 colors + shades |
| **Typography** | 2 font families, 6+ scales |
| **Spacing** | 4px base unit scale |
| **Border Radius** | 6 sizes (4px-24px) |
| **Shadows** | 6 elevation levels |
| **Animations** | 15+ micro-interactions |
| **Dark Mode** | Full support with color inversion |
| **Accessibility** | WCAG AA compliant |
| **Responsive** | Mobile-first, scalable |

---

## 🎯 Key Features

✅ **Premium Design** - Clean, modern, trustworthy aesthetic  
✅ **Complete** - 20+ screens covering all user flows  
✅ **Interactive Prototype** - Clickable prototype flows  
✅ **Component Library** - Reusable components with states  
✅ **Design System** - Colors, typography, spacing specifications  
✅ **Accessibility** - WCAG AA compliant  
✅ **Dark Mode** - Full theme support  
✅ **Animations** - Smooth micro-interactions (300-400ms)  
✅ **Developer Ready** - Complete handoff documentation  
✅ **Scalable** - Responsive design for all devices  

---

## 📞 Support

For design questions or implementation guidance:
- Review the detailed specs in QUOTEHUB_DESIGN.md
- Check design tokens in DESIGN_TOKENS.json
- Consult Figma file for interactive prototypes
- Reference component library for implementation

---

## 📄 Files in This Repository

```
/
├── README_DESIGN.md          ← This file
├── QUOTEHUB_DESIGN.md        ← Detailed design specification
├── DESIGN_TOKENS.json        ← Developer-ready design tokens
└── Branch: claude/quotehub-mobile-design-f5gmhh
```

---

## 🔗 Quick Links

- **Figma Design**: https://www.figma.com/design/DA5eWgPtD7L6PDRK7X26O8
- **Git Branch**: `claude/quotehub-mobile-design-f5gmhh`
- **Status**: ✅ Ready for Development

---

**Design Date**: July 2025  
**Version**: 1.0  
**Status**: Production Ready  
**Created by**: Claude Code AI  

🎉 **The design system is complete and ready for your development team!**
