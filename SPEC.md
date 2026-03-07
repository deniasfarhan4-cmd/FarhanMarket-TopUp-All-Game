# FLX Setting - Android Tool App Specification

## Project Overview
- **Project Name**: FLX Setting
- **Type**: Web-based Android Application (PWA)
- **Core Functionality**: A collection of useful utility tools with a modern, app-like interface featuring cool animations
- **Target Users**: Android users looking for handy utility tools

## UI/UX Specification

### Layout Structure
- **Navigation**: Bottom tab navigation (like a real Android app)
- **Pages**: 
  - Home (Dashboard with tool cards)
  - Tools (All available tools)
  - Settings (App preferences)
- **Responsive**: Optimized for mobile (360px width) but works on desktop

### Visual Design

#### Color Palette
- **Primary**: #0F0F23 (Deep dark blue)
- **Secondary**: #1A1A3E (Dark purple-blue)
- **Accent**: #00D9FF (Cyan neon)
- **Accent Secondary**: #FF006E (Pink neon)
- **Accent Tertiary**: #7B2FFF (Purple)
- **Text Primary**: #FFFFFF
- **Text Secondary**: #8B8BA7
- **Card Background**: rgba(26, 26, 62, 0.8)
- **Gradient**: linear-gradient(135deg, #0F0F23 0%, #1A1A3E 50%, #0F0F23 100%)

#### Typography
- **Font Family**: 'Orbitron' for headings (futuristic), 'Poppins' for body
- **Headings**: 24px-32px, bold, letter-spacing: 2px
- **Body**: 14px-16px, regular
- **Tool Names**: 18px, semi-bold

#### Spacing
- **Container Padding**: 20px
- **Card Padding**: 16px
- **Card Gap**: 16px
- **Border Radius**: 20px for cards, 50px for buttons

#### Visual Effects
- **Glassmorphism**: Cards with backdrop-filter blur
- **Neon Glow**: Box-shadow with accent colors
- **Gradient Borders**: Animated gradient borders on cards
- **Floating Particles**: Animated background particles

### Components

#### 1. App Header
- Logo with glow effect
- App name "FLX Setting"
- Animated gradient text

#### 2. Tool Cards
- Icon (using emoji or simple SVG)
- Tool name
- Brief description
- Gradient border on hover
- Scale animation on tap

#### 3. Bottom Navigation
- 3 tabs: Home, Tools, Settings
- Active state with neon glow
- Smooth transition animations

#### 4. Tool Views
- Each tool opens in full-screen modal
- Smooth slide-up animation
- Close button with animation

### Animations

#### Background
- Floating geometric shapes (circles, triangles)
- Gradient mesh moving slowly
- Particle system

#### Interactions
- Card hover: scale(1.05) + glow
- Card tap: scale(0.95) + ripple
- Tab switch: slide + fade
- Tool open: slide up from bottom
- Button press: pulse effect

## Functionality Specification

### Tools Included

1. **IP Address Finder** - Display user's IP address
2. **Color Picker** - Pick colors from a palette
3. **Text to Speech** - Convert text to speech
4. **Unit Converter** - Convert length, weight, temperature
5. **QR Code Generator** - Generate QR codes
6. **Password Generator** - Create secure passwords
7. **Base64 Encoder/Decoder** - Encode/decode text
8. **JSON Formatter** - Format and validate JSON
9. **Timestamp Converter** - Convert Unix timestamps
10. **Device Info** - Show device information

### User Interactions
- Tap tool card → Open tool modal
- Swipe down → Close modal
- Tap bottom nav → Switch tabs with animation
- Pull to refresh on home (visual only)

## Acceptance Criteria

1. ✅ App loads with animated background
2. ✅ All 10 tools are accessible and functional
3. ✅ Smooth animations on all interactions
4. ✅ Bottom navigation works correctly
5. ✅ Responsive on mobile and desktop
6. ✅ Glassmorphism effect visible on cards
7. ✅ Neon glow effects on interactive elements
8. ✅ No console errors
9. ✅ Fast loading time

