# GitHub Copilot Instructions

<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

## Project Overview
This is a modern React TypeScript portfolio website built with Vite. The project emphasizes:

- **Modular Architecture**: Each component has its own separate CSS file
- **Futuristic Design**: Modern UI with animations and smooth transitions
- **Scalable Project Showcase**: Designed to elegantly display 100+ projects
- **Performance**: Optimized for smooth scrolling and interactions

## Development Guidelines

### Component Structure
- Each component should have its own folder with `.tsx` and `.module.css` files
- Use CSS modules for styling to maintain scope isolation
- Implement proper TypeScript interfaces for all props

### Styling Approach
- Use CSS custom properties (variables) for consistent theming
- Implement responsive design with mobile-first approach
- Leverage CSS Grid and Flexbox for layouts
- Use Framer Motion for animations and transitions

### Performance Considerations
- Implement lazy loading for project images
- Use React.memo for expensive components
- Optimize animations for 60fps performance
- Consider virtualization for large project lists

### Technology Stack
- React 18 with TypeScript
- Vite for build tooling
- Framer Motion for animations
- Lucide React for icons
- CSS Modules for styling
- EmailJS for contact form functionality
