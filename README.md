# GoalSetter - Personal Goal Tracker

🎯 **A modern, interactive, and fully responsive personal goal tracking application built with React, Tailwind CSS, and Framer Motion.**

## 🌟 Features

### ✨ Core Functionality
- **Interactive Goal Cards** with animated circular progress bars
- **Add/Edit/Delete Goals** with smooth modal animations
- **Category System** with color-coded tags (Fitness, Work, Education, Finance, Personal)
- **Progress Tracking** with visual percentage indicators
- **Dual View Modes** - Grid and List layouts
- **Dark Mode Toggle** with smooth transitions
- **LocalStorage Persistence** - saves all data locally

### 🎨 Design & UX
- **Modern, Clean Interface** inspired by Notion/Trello
- **Smooth Animations** using Framer Motion
- **Responsive Design** - Mobile, Tablet, and Desktop optimized
- **Motivational Quotes** that change on refresh
- **Confetti Animation** 🎉 when goals are completed
- **Floating Action Button** for quick goal creation
- **Background Animations** for visual appeal
- **Drag & Drop** goal reordering

### 🎯 Goal Management
- Set goal titles and target values
- Track current progress
- Categorize goals with colored tags
- Edit goals with pre-filled forms
- Delete goals with confirmation
- Visual completion indicators

## 🚀 Getting Started

1. **Clone and Install**
   ```bash
   npm install
   ```

2. **Start Development Server**
   ```bash
   npm run dev
   ```

3. **Open in Browser**
   Navigate to `http://localhost:3000`

## 📱 Responsive Breakpoints

- **Mobile (< 768px)**: Single column layout
- **Tablet (768px - 1024px)**: Two column grid
- **Desktop (> 1024px)**: Three to four column grid

## 🎨 Technology Stack

- **React 18** - UI Framework
- **Tailwind CSS** - Styling and responsive design
- **Framer Motion** - Animations and transitions
- **React Circular Progressbar** - Animated progress circles
- **Canvas Confetti** - Celebration animations
- **React Beautiful DnD** - Drag and drop functionality
- **Vite** - Build tool and development server

## 🎯 Usage

1. **Add Your First Goal**
   - Click the floating "+" button or "Create My First Goal"
   - Fill in goal details (title, category, target, current progress)
   - Save to see your goal card appear

2. **Track Progress**
   - Edit goals to update current progress
   - Watch the circular progress bar animate
   - Get confetti celebration when reaching 100%

3. **Organize Goals**
   - Switch between Grid and List views
   - Drag and drop to reorder goals
   - Filter by color-coded categories

4. **Customize Experience**
   - Toggle dark mode for better viewing
   - Refresh motivational quotes for inspiration
   - Enjoy smooth animations throughout

## 🎉 Special Features

- **Motivational Quotes**: Random inspirational messages
- **Completion Celebrations**: Confetti animation for 100% goals
- **Persistent Storage**: All data saved locally
- **Accessibility**: Keyboard navigation support
- **Performance**: Optimized animations and rendering

## 🔧 Project Structure

```
src/
├── components/           # React components
│   ├── Navbar.jsx       # Header with dark mode toggle
│   ├── GoalCard.jsx     # Individual goal display
│   ├── GoalModal.jsx    # Add/Edit goal form
│   ├── ViewToggle.jsx   # Grid/List view switcher
│   └── BackgroundAnimation.jsx # Animated background
├── data/                # Static data
│   └── categories.js    # Goal categories configuration
├── utils/               # Utility functions
│   ├── localStorage.js  # Data persistence
│   └── helpers.js       # Helper functions
├── App.jsx             # Main application component
├── main.jsx            # Application entry point
└── index.css           # Global styles and Tailwind directives
```

## 🎨 Color Scheme

- **Fitness**: Green (#10B981)
- **Work**: Blue (#3B82F6)
- **Education**: Purple (#8B5CF6)
- **Finance**: Yellow (#F59E0B)
- **Personal**: Pink (#EC4899)

## 🚀 Performance Features

- **Lazy Loading**: Components load efficiently
- **Optimized Animations**: Smooth 60fps animations
- **Responsive Images**: Optimized for all screen sizes
- **Fast Hot Reload**: Instant development feedback

---

**Built with ❤️ for productivity enthusiasts and goal achievers!**