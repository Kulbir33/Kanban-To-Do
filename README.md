
# Kanban Board Project

## Overview

This Kanban Board Project is a dynamic web application that allows users to manage tasks through a visually appealing Kanban board. The application features a modern design with smooth animations, dark mode support, and various interactive elements. Built with React (or Next.js) and Firebase Firestore, the project also incorporates beautiful styling and transitions to enhance user experience.

## Features

- **Kanban Board:** Manage tasks and columns in a flexible board layout.
- **Dark Mode:** Seamless dark mode support for improved usability in low-light environments.
- **Responsive Design:** Mobile and desktop-friendly design with smooth transitions.
- **Task Management:** Add, edit, and delete tasks with ease.
- **Interactive Elements:** Enhanced with animations and transitions for a polished look.
- **Theme Toggle:** Switch between light and dark themes.
- **Modal Dialogs:** For task details, deletions, and other interactions.

## Technologies

- **Frontend:**
  - React or Next.js
  - CSS/SCSS for styling
  - Animations using CSS transitions and keyframes

- **Backend:**
  - Firebase Firestore for real-time data management

- **Deployment:**
  - Vercel for hosting

## Setup Instructions

### Prerequisites

- Node.js
- npm or yarn

### Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd <repository-folder>

   ## Deployment

Deploy the application to Vercel using the Vercel CLI or through their web interface.

## Design and Styling

### General Styles

- **Background and Text Colors:**
  - Light theme: `#f4f7fd`, `#20212c` (dark mode)
  - Text colors: `#828fa3`, `#635fc7` (primary color)

- **Typography:**
  - **Heading XL:** Font size 26px, line height 32px
  - **Heading L:** Font size 20px, line height 26px
  - **Heading M:** Font size 16px, line height 22px
  - **Heading S:** Font size 14px, line height 18px
  - **Text L:** Font size 14px, line height 20px
  - **Text M:** Font size 13px, line height 18px

### Animations and Transitions

- **Smooth Color Transitions:** Applied to text and background colors.
- **Hover Effects:** Button and sidebar hover effects with color and background changes.
- **Modal Animations:** Smooth transitions for modal dialogs and form elements.

## File Structure

- **`/src`**: Source code
  - **`/components`**: React components
  - **`/styles`**: CSS/SCSS files
  - **`/utils`**: Utility functions
- **`/public`**: Static assets (images, icons)
- **`/firebase`**: Firebase configuration and initialization

## Development

### Available Scripts

- **Start Development Server:**

  ```bash
  npm start
  # or
  yarn start

