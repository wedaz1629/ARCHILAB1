# ARCHILAB - Laboratory Management System

## Overview

ARCHILAB is a laboratory management system designed for tracking and managing cassettes and slides. The application provides a complete workflow for registering, searching, editing, and tracking laboratory specimens with a comprehensive history system. Built with modern web technologies, it features a responsive interface optimized for laboratory environments with real-time data management capabilities.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript for type safety and modern component patterns
- **UI Library**: Shadcn/ui components built on Radix UI primitives providing accessible, customizable design system
- **Styling**: Tailwind CSS with custom design tokens and CSS variables for theming
- **Routing**: Wouter for lightweight client-side routing
- **State Management**: TanStack Query (React Query) for server state management with caching and synchronization
- **Form Management**: React Hook Form with Zod validation for robust form handling and validation

### Backend Architecture
- **Runtime**: Node.js with Express.js framework for RESTful API endpoints
- **Development**: TSX for TypeScript execution in development with hot reloading
- **Build System**: ESBuild for fast production bundling with ES modules support
- **Storage**: In-memory storage with planned PostgreSQL integration using Drizzle ORM
- **API Design**: RESTful endpoints with standardized error handling and request/response patterns

### Data Storage Solutions
- **ORM**: Drizzle ORM configured for PostgreSQL with type-safe database operations
- **Schema**: Centralized schema definitions with automatic TypeScript type generation
- **Validation**: Zod schemas for runtime validation matching database schema
- **Migrations**: Drizzle Kit for database schema migrations and versioning

### Key Design Patterns
- **Shared Types**: Common schema definitions between frontend and backend for type consistency
- **Component Composition**: Reusable UI components with proper separation of concerns
- **Error Boundaries**: Comprehensive error handling with user-friendly error messages
- **Responsive Design**: Mobile-first approach with adaptive layouts for different screen sizes

### Development Experience
- **Vite Integration**: Fast development server with Hot Module Replacement
- **TypeScript Configuration**: Strict type checking with path mapping for clean imports
- **Code Organization**: Clear separation between client, server, and shared code
- **Replit Integration**: Optimized for Replit development environment with cartographer plugin

## External Dependencies

### Database
- **Neon Database**: Serverless PostgreSQL database with connection pooling
- **Connection**: Environment-based configuration with DATABASE_URL

### UI and Styling
- **Radix UI**: Comprehensive primitive components for accessibility and customization
- **Tailwind CSS**: Utility-first CSS framework with custom configuration
- **Lucide React**: Icon library for consistent iconography
- **Google Fonts**: Poppins font family for typography

### Development and Build Tools
- **Vite**: Frontend build tool and development server
- **ESBuild**: JavaScript bundler for production builds
- **PostCSS**: CSS processing with Tailwind CSS integration
- **TypeScript**: Static type checking and compilation

### Data Management
- **TanStack Query**: Server state management with caching, background updates, and optimistic updates
- **React Hook Form**: Form state management with performance optimization
- **Date-fns**: Date manipulation and formatting utilities

### Validation and Schema
- **Zod**: Runtime type validation and schema definition
- **Drizzle Zod**: Integration between Drizzle ORM and Zod for consistent validation

### Additional Libraries
- **Class Variance Authority**: Utility for managing component variants
- **CLSX**: Conditional className utility for dynamic styling
- **Embla Carousel**: Carousel component for data presentation
- **CMDK**: Command palette interface for improved user experience