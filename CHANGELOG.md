# Changelog

All notable changes to Sortopia will be documented in this file.

## [1.1.0] - 2025-11-16

### ✨ Added

#### 📁 **Saved Games System**
- **Auto-Save Feature**: Games are automatically saved to local storage when played
- **Saved Games Panel**: New section in hamburger menu to manage your game collection
- **Game Library**: View all saved games with metadata (item count, save date, play count)
- **Quick Load**: One-click loading of any saved game
- **Smart Storage**: Games keyed by title with automatic deduplication

#### 🔗 **Enhanced Sharing**
- **Copy Share Links**: New 🔗 icon on each saved game for instant URL copying
- **Modern Clipboard API**: Uses latest browser clipboard features with fallback support
- **Toast Notifications**: Non-blocking feedback system for user actions
- **One-Click Sharing**: Copy shareable URLs directly from saved games panel

#### 🎮 **Improved User Experience**
- **Streamlined Edit Flow**: "Save Changes" now automatically switches to play mode
- **Immediate Testing**: Edit → Save → Play workflow is now seamless
- **Clean Interface**: Removed item numbers for more space and cleaner appearance
- **Enhanced Visual Feedback**: Toast notifications replace blocking alert dialogs

### 🔄 Changed

#### 🎨 **Visual Improvements**
- **Cleaner Item Display**: Removed numbered circles from quiz items
- **More Content Space**: Items now display with full width for better readability
- **Modern Notifications**: Replaced alert() dialogs with sleek toast notifications
- **Enhanced Button Layout**: Share and delete icons with proper spacing and hover effects

#### ⚡ **Performance & UX**
- **Faster Navigation**: Automatic mode switching after saving edits
- **Reduced Clicks**: Streamlined workflows require fewer user interactions
- **Better Mobile Experience**: Optimized button sizes and toast positioning for mobile

### 🛠️ **Technical**

#### 🏗️ **Architecture Updates**
- **Local Storage Schema**: New `savedGames` storage system
- **Simplified DOM Handling**: Removed item numbering complexity
- **Modern JavaScript**: Updated clipboard API usage with graceful fallbacks
- **Component System**: Modular toast notification system

#### 📱 **Mobile Optimizations**
- **Responsive Toast**: Mobile-optimized notification sizing and positioning
- **Touch-Friendly Actions**: Properly sized share and delete buttons
- **Improved Accessibility**: Added tooltips and ARIA labels

### 🎯 **User Benefits**
- **Game Collection**: Build and manage a personal library of challenges
- **Easy Sharing**: Share any saved game with a single click
- **Faster Workflow**: Edit and test challenges without manual navigation
- **Cleaner Interface**: Focus on content, not interface clutter
- **Better Feedback**: Clear, non-disruptive notifications

---

## [1.0.0] - 2025-11-16

### 🎉 Initial Release

**Sortopia** is now ready for the world! A magical sorting game that makes organizing fun and interactive.

### ✨ Features

#### 🎮 **Core Gameplay**
- **Drag & Drop Interface**: Smooth, intuitive reordering with visual feedback
- **Mobile-Optimized**: Touch-friendly drag and tap-to-select functionality  
- **Answer Checking**: Instant feedback with color-coded correct/incorrect results
- **Shuffle Feature**: Randomize items for fresh attempts
- **Try Again**: Restart challenges with new random order

#### 🛠️ **Challenge Creation & Editing**
- **Custom Challenges**: Create personalized sorting challenges
- **Dynamic Titles**: First line becomes the challenge name
- **Edit Mode**: Modify existing challenges with save/reset options
- **Smart Navigation**: Button text changes from "Create" to "Edit" based on context

#### 📱 **Mobile Experience**
- **Prevented Text Selection**: No more accidental text highlighting on mobile
- **Dual Interaction Modes**:
  - Traditional hold-and-drag
  - Modern tap-to-select-and-place
- **Visual Feedback**: Golden selection highlights and green drop targets
- **Touch Optimized**: Proper button sizes and touch areas

#### 🌐 **Sharing & Storage**
- **URL Sharing**: Base64-encoded challenges in query parameters (no server needed!)
- **Local Storage**: Auto-save progress and resume where you left off
- **Offline Capable**: Works completely without internet connection
- **Reset Functionality**: Clear all data for fresh start

#### 🎨 **User Interface**
- **Clean Design**: Hamburger menu keeps interface uncluttered during gameplay
- **Dynamic Header**: Shows challenge title instead of generic branding during play
- **Responsive Layout**: Beautiful on phones, tablets, and desktop
- **Modern Styling**: Gradients, animations, and smooth transitions
- **Professional Feel**: Each challenge feels like a dedicated app

#### 🔧 **Technical Excellence**
- **Single File**: Complete game in one HTML file with embedded CSS/JS
- **No Dependencies**: Pure vanilla web technologies
- **GitHub Pages Ready**: Deploy anywhere that serves static files
- **Cross-Browser**: Works on all modern browsers
- **Accessible**: Keyboard and screen reader friendly

### 📋 **Perfect For**
- Educational games (historical timelines, scientific processes)
- Team building activities and icebreakers
- Party games and social challenges  
- Brain training and memory exercises
- Kids learning sequencing and ordering

### 🎯 **Example Challenges**
- Historical events timeline
- Movie franchise chronology
- Scientific discovery milestones
- Book series reading order
- Recipe steps sequence
- And unlimited custom challenges!

### 🚀 **Getting Started**
1. Open `index.html` in any modern web browser
2. Click "Create Challenge" to make your first sorting game
3. Share the generated URL with friends and family
4. Enjoy watching others try to get the perfect order!

### 🙏 **Credits**
Built with ❤️ for the love of sorting and organization.

*Sortopia - Where everything finds its perfect place* ✨

---

## How to Use This Changelog

- **Added** for new features
- **Changed** for changes in existing functionality  
- **Deprecated** for soon-to-be removed features
- **Removed** for now removed features
- **Fixed** for any bug fixes
- **Security** in case of vulnerabilities