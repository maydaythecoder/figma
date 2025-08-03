# Learninja Dashboard

A responsive learning dashboard built with HTML and Tailwind CSS, converted from a Figma design.

## Features

- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices
- **Modern UI**: Clean, modern interface with smooth gradients and rounded corners
- **Interactive Elements**: Hover effects, notifications, and accessible buttons
- **Dashboard Components**:
  - Sidebar navigation with active states
  - Course cards with progress indicators
  - Analytics charts (Hours Spent & Performance)
  - Leader board with rankings
  - Profile section with calendar and todo list

## Structure

```text
├── index.html          # Main dashboard page
├── README.md          # Documentation
└── .git/              # Git repository
```

## Components

### Sidebar Navigation

- Logo with brand colors
- Navigation menu with icons
- Notification badges
- Active state indicators

### Main Content Area

- Welcome header with search functionality
- Course cards (HTML & CSS, Branding Design, Motion Design)
- Analytics section with charts
- Leader board table

### Profile Sidebar

- User profile with verification badge
- Interactive calendar
- Todo list with task management
- Edit profile functionality

## Design System

### Colors

- **Primary**: `#3BAFA8` (Teal)
- **Secondary**: `#FF9053` (Orange)
- **Accent**: `#F94874` (Pink)
- **Dark**: `#1F1C3B` (Dark Blue)
- **Light**: `#F5F7F9` (Light Gray)
- **Muted**: `#85878D` (Gray)

### Typography

- **Font Family**: Inter (Google Fonts)
- **Weights**: 400 (Regular), 500 (Medium), 600 (SemiBold), 700 (Bold)

### Spacing

- Consistent spacing using Tailwind's spacing scale
- Rounded corners: `rounded-xl`, `rounded-3xl`
- Padding: `p-6`, `p-8`
- Margins: `mb-8`, `gap-6`

## Accessibility

- Semantic HTML structure
- ARIA labels for interactive elements
- Proper heading hierarchy
- Keyboard navigation support
- Screen reader friendly

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Getting Started

1. Clone the repository
2. Open `index.html` in your browser
3. No build process required - uses CDN for Tailwind CSS

## Customization

### Adding New Courses

Add new course cards in the main content area:

```html
<div class="bg-gradient-to-br from-[color]-100 to-[color]-200 rounded-xl p-6 h-44 relative">
    <!-- Course content -->
</div>
```

### Modifying Colors

Update the Tailwind config in the HTML head:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#YOUR_COLOR',
                // ... other colors
            }
        }
    }
}
```

## Performance

- Lightweight implementation
- No JavaScript dependencies
- Optimized SVG icons
- Efficient CSS with Tailwind's utility classes

## License

This project is open source and available under the MIT License.
