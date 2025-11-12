# Learnitab Kanban

A simple and beautiful Kanban board application with persistent custom banner images.

## Features

- **Kanban Board**: Organize tasks across multiple boards (Todo, In Progress, Review, Done)
- **Custom Banners**: 
  - Upload custom banner images from your device
  - Add banners via URL
  - Banner gallery to save and switch between multiple banners
  - All uploaded banners are stored in localStorage and persist after refresh
- **Theme Customization**: Choose from 9 color themes
- **Drag & Drop**: Move tasks between boards easily
- **Task Management**: Add, edit, duplicate, and delete tasks
- **Persistent Storage**: All data saved to localStorage
- **Cache Management**: Auto-refresh on version updates to ensure latest features

## New Banner Features (v2.0.0)

### Upload Custom Banners
- Upload image files directly from your device (max 2MB)
- Supports all common image formats

### Banner Gallery
- Automatically saves all uploaded banners to a gallery
- Gallery stores up to 12 banners
- Click any banner in the gallery to use it
- Remove banners from gallery by hovering and clicking the X button
- Selected banner is highlighted with a blue ring

### Persistent Storage
- All uploaded banners persist after refresh
- No need to re-upload your favorite banners
- Cache-busting ensures updates are always visible

## Usage

1. Enter your name on the welcome screen
2. Go to Settings (gear icon) to customize:
   - Upload or link a banner image
   - Select from your saved banner gallery
   - Choose a theme color
   - Set date format preference
3. Create tasks by clicking "Add Task" on any board
4. Drag and drop tasks between boards to update their status
5. Click on a task to view details, edit, or duplicate

## Technical Details

- Built with Alpine.js for reactive components
- Styled with Tailwind CSS
- No backend required - runs entirely in the browser
- All data stored in localStorage for persistence
