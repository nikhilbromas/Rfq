# QuoteHub - Mobile App Design System

## Overview
QuoteHub is a premium mobile RFQ (Request for Quotation), contractor, vendor, and skilled worker marketplace for Android and iOS. The design combines clean minimalism with premium SaaS aesthetics, inspired by Airbnb, Uber, Linear, Revolut, Notion, Upwork, and Apple.

## 📁 Design Files
**Figma Design**: [QuoteHub - Mobile Design](https://www.figma.com/design/DA5eWgPtD7L6PDRK7X26O8)

## 🎨 Design System

### Color Palette
- **Primary**: `#6C4DFF` - Main brand color (purple)
- **Secondary**: `#7B61FF` - Secondary purple
- **Accent**: `#00C896` - Green accent (success/approve)
- **Warning**: `#FFB547` - Orange warning
- **Danger**: `#FF5A5F` - Red error
- **Background**: `#F8F9FC` - Light background
- **Dark Background**: `#0F172A` - Dark mode background
- **Card**: `#FFFFFF` - Card/surface color
- **Success**: `#2ECC71` - Success green
- **Text Primary**: `#111827` - Main text
- **Text Secondary**: `#6B7280` - Secondary text
- **Border**: `#E5E7EB` - Border/divider

### Typography

#### Headings
- **Font**: SF Pro Display
- **Weight**: Bold (700)
- **Sizes**: 32px (Large), 28px (Medium), 24px (Small)

#### Body Text
- **Font**: Inter
- **Weight**: Medium (500) or Regular
- **Sizes**: 16px (Large), 14px (Medium), 12px (Small)

#### Labels
- **Font**: Inter
- **Weight**: Semi Bold (600)
- **Size**: 12px

#### Numbers
- **Font**: SF Pro Display
- **Weight**: Bold (700)
- **Sizes**: 28px and larger

### Spacing & Radius
- **Border Radius**: 20–24px (cards), 12px (buttons), 8px (small elements)
- **Padding**: 16px, 20px (content), 12px (elements)
- **Gap/Spacing**: 8px, 12px, 16px, 24px (hierarchical)
- **Shadow**: Soft layered (0px 4px 12px, opacity 8%)

## 📱 Screens Built

### 1. Home Dashboard
- **Components**: 
  - Status bar with time
  - Personalized greeting ("Good Morning, [Name]")
  - Search bar with category filters
  - RFQ cards with budget, deadline, bid count
  - Trending projects section
  - Recommended contractors
  - Smooth infinite scroll animations

### 2. RFQ Feed
- **Components**:
  - Large image/hero cards
  - Company logo with verification badge
  - Budget range display
  - Deadline countdown
  - Location indicator
  - Bid count badge
  - Bookmark/Save button
  - Share button
  - "Bid Now" primary action
  - Stagger animation on scroll

### 3. RFQ Details
- **Components**:
  - Hero image at top
  - Sticky back navigation button
  - Company profile card
  - Budget badge (primary highlight)
  - Project timeline
  - Requirements section (expandable)
  - Scope of work details
  - Attachments viewer
  - Bid history
  - Sticky "Place Bid Now" bottom button
  - Animated expandable sections

### 4. Place Bid
- **Components**:
  - Quote amount input with currency symbol
  - Estimated timeline (days) picker
  - Warranty/guarantee field
  - Proposal/description textarea
  - Document upload area
  - Animated submit button
  - Success celebration animation after submission

### 5. Chat/Messaging
- **Components**:
  - WhatsApp-inspired clean interface
  - Message list with sender avatar
  - Typing indicator animation
  - Voice note button
  - Image/PDF attachment preview
  - Video call button
  - Quotation discussion thread
  - Mention/@ mentions feature
  - Read receipts (single/double check marks)
  - Message reactions (emoji)

### 6. My Bids
- **Components**:
  - Tab navigation (Submitted, Viewed, Shortlisted, Awarded, Completed, Rejected)
  - Bid status timeline cards
  - Progress indicator per bid
  - Expandable details
  - Quick actions (withdraw, update, resubmit)

### 7. Contracts & Escrow
- **Components**:
  - Digital contract cards
  - Project timeline visualization
  - Milestone breakdown
  - Inspection checklist
  - Document storage
  - Payment schedule
  - Completion status tracker
  - Release payment button with confirmation

### 8. Wallet & Payments
- **Components**:
  - Glassmorphism balance card
  - Available balance display
  - Escrow balance section
  - Pending release amount
  - Income graph/chart
  - Recent transaction list
  - Withdraw button
  - Linked bank accounts section
  - Escrow history
  - Animated counters

### 9. Worker/Contractor Profile
- **Components**:
  - Large profile header with background
  - Professional photo with verification badge
  - Skills section (tags)
  - Experience timeline
  - Certificates/credentials
  - Portfolio gallery (project cards)
  - Completed projects counter
  - Star rating with review count
  - Success rate percentage
  - Hourly/Daily rate display
  - Availability status
  - "Book Now" primary action

### 10. Notifications
- **Components**:
  - Grouped notification cards
  - Unread badges
  - Swipe-to-dismiss actions
  - Status icons (checkmark, clock, alert)
  - Timestamp labels (relative: "2h ago")
  - Filter chips (New, Messages, Bids, Payments)

### 11. Search
- **Components**:
  - AI-powered search bar
  - Voice search button
  - Category filter chips
  - Budget range slider
  - Distance/location slider
  - Ratings filter
  - Availability filter
  - Map/List toggle view

## 🧩 Component Library

### Buttons
- **Primary Button**: Solid purple (#6C4DFF), white text
- **Secondary Button**: Solid secondary purple (#7B61FF)
- **Accent Button**: Solid green (#00C896)
- **Outline Button**: White background, colored border, colored text
- **States**: Default, Hover, Active, Disabled
- **Radius**: 12px
- **Height**: 48px standard

### Cards
- **Default Card**: White background, light border, soft shadow
- **RFQ Card**: Image hero, company logo, budget badge, deadline, bid count
- **Bid Card**: Quote amount, timeline, warranty info, status
- **Contract Card**: Project title, milestone progress, release button
- **Radius**: 16–20px
- **Padding**: 16px

### Inputs & Forms
- **Text Input**: 44–48px height, 12px border, rounded corners
- **Dropdown Select**: Chevron indicator, open state animation
- **Date Picker**: Calendar interface, date range selection
- **Textarea**: Multi-line with character counter
- **Radio/Checkbox**: Custom styled, smooth animation
- **Slider**: Dual-range (budget, distance)

### Badges & Tags
- **Status Badge**: Colored background, bold label
- **Verification Badge**: ✓ checkmark icon
- **Category Tag**: Outlined style, category icon
- **Count Badge**: Circle with number

### Progress Indicators
- **Progress Bar**: Linear, animating fill
- **Step Indicator**: Current step highlight
- **Milestone Progress**: Visual breakdown
- **Circular Progress**: For percentage completion

### Bottom Navigation
- **5 Main Tabs**: Home, RFQs, Create (center FAB), Messages, Profile
- **Center Floating Action Button**: Large gradient button for "Create New RFQ"
- **Active State**: Color change, label emphasis
- **Safe Area**: Respects phone notch/home indicator

## 🎬 Motion & Animations

### Micro-interactions (300–400ms easing)
- **Button Press**: Scale down 95%, instant feedback
- **Card Hover**: Elevation increase (0 → 8px shadow)
- **Card Expansion**: Smooth height animation
- **Page Transition**: Fade + slide (300ms)
- **Shared Element Transition**: Card to details screen
- **FAB Morph**: Circle → Plus icon animation
- **Loading Shimmer**: Animated gradient skeleton
- **Pull-to-Refresh**: Spring bounce on release
- **Success Animation**: Checkmark with confetti particles
- **Error Animation**: Shake + red pulse
- **Swipe Gestures**: Dismiss on swipe-left/right
- **Long Press**: Scale up + haptic feedback
- **Bottom Sheet**: Slide up from bottom (300ms)
- **Drag & Drop**: Visual feedback during upload

## 🔌 Prototype Flow

### Main User Journey
```
Splash Screen → Login/Signup → Home Dashboard 
  ↓
  Browse RFQs → RFQ Details → Place Bid 
  ↓
  Chat with Client → View Contracts 
  ↓
  Escrow Payment Release → Wallet → Profile
```

### Tab Navigation
- **Home**: All screens accessible via navigation
- **RFQs**: Feed view, filtering, sorting
- **Create**: Multi-step wizard (6 steps)
- **Messages**: Chat list, conversation detail
- **Profile**: User profile, settings, credentials

## 📐 Specifications

### Device Support
- **iPhone**: 375×812 (base size, scales for all sizes)
- **iPad**: Responsive design considerations
- **Android**: Portrait orientation optimized

### Accessibility
- **Color Contrast**: WCAG AA compliant (4.5:1 text)
- **Touch Targets**: Minimum 48×48px
- **Font Sizes**: Readable at 12px minimum (body)
- **Semantic Structure**: Proper heading hierarchy

### Dark Mode
- **Background**: `#0F172A` (dark navy)
- **Cards**: `#1A2637` (slightly lighter)
- **Text**: Inverted (white/light grays)
- **All colors**: Adjusted for contrast

## 🚀 Developer Handoff

### What's Included
✅ 9 production-ready screens
✅ Reusable component library
✅ Complete color system
✅ Typography specifications
✅ Spacing/padding guidelines
✅ Animation timings (300–400ms easing)
✅ Prototype flows and interactions

### Next Steps
1. **Developers**: Use this file as a reference
2. **Implement**: Build components library in React Native/Flutter
3. **Test**: Verify touch targets, animations, accessibility
4. **Polish**: Refine micro-interactions and transitions
5. **QA**: Cross-device testing (iOS/Android)

## 📝 Notes
- All components use Auto Layout for scalability
- Colors/styles easily swappable via design tokens
- Prototype includes realistic transitions
- Ready for production implementation
- Consider adding dark mode switch in settings

---

**Design Date**: July 2024  
**Designer**: Claude Code  
**Status**: Ready for Development
