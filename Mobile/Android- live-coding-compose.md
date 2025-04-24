# Jetpack Compose UI Live Coding Tasks for Technical Interviews

This document contains well-defined live coding tasks for evaluating candidates' Jetpack Compose UI skills across three different engineering levels. Each task includes a clear problem statement and specific requirements to assess the appropriate skills for each level.

## Table of Contents
1. [Beginner Level (SDE-1)](#beginner-level-sde-1)
2. [Intermediate Level (SDE-2)](#intermediate-level-sde-2)
3. [Expert Level (SDE-3)](#expert-level-sde-3)

## Beginner Level (SDE-1)

### Task 1: Profile Card
**Problem Statement:**
Create a simple profile card using Jetpack Compose that displays:
- A circular avatar image (you can use a placeholder)
- The user's name as a headline
- Their job title as a subtitle
- A short bio as body text
- All elements should be centered and stacked vertically
- Apply appropriate spacing between elements
- Add a subtle background color or border to frame the card

The component should accept parameters for the name, job title, bio text, and image resource to allow for reusability.

### Task 2: Custom Button with Loading State
**Problem Statement:**
Implement a custom button component in Jetpack Compose that:
- Takes a text parameter for the button label
- Has a primary and secondary state (visually distinct)
- Includes a loading state that shows a circular progress indicator instead of text
- Disables click events while in loading state
- Maintains consistent width between loading and normal states
- Has appropriate padding and rounded corners
- Demonstrates proper state management using Compose state

### Task 3: Tabbed Navigation Interface
**Problem Statement:**
Create a basic tabbed navigation interface that:
- Shows 3 tabs at the top of the screen with icons and labels
- Allows switching between tabs by tapping
- Highlights the currently selected tab
- Displays different simple content for each tab (can be placeholder text)
- Animates the tab indicator when switching between tabs
- Use composable functions to organize the code structure cleanly
- Ensure tabs are equally spaced and responsive to screen width

### Task 4: Interactive List with Expandable Items
**Problem Statement:**
Implement a list in Jetpack Compose that:
- Displays at least 5 items with a title and description
- Initially shows only the title for each item
- When an item is clicked, it expands to show the description with an animation
- Only one item can be expanded at a time
- Expanded items have a different background color
- Each item should have appropriate padding and spacing
- Use LazyColumn for the list implementation

### Task 5: Form with Input Validation
**Problem Statement:**
Create a simple registration form in Jetpack Compose with:
- Input fields for name, email, and password
- Real-time validation with error messages (e.g., email format, password strength)
- A submit button that is only enabled when all inputs are valid
- Clear visual indication of validation state (success/error)
- Password field should have a toggle to show/hide the password
- Implement proper keyboard options for each field type
- Handle focus management between fields

### Task 6: Rating Component
**Problem Statement:**
Build a star rating component that:
- Displays 5 stars in a row
- Allows users to tap to set a rating
- Supports partial ratings (half stars)
- Shows visual feedback when hovering or selecting stars
- Includes an optional label to display the current rating value
- Is reusable and customizable (star size, colors, etc.)
- Demonstrates proper state management

### Task 7: Animated Counter
**Problem Statement:**
Implement a numerical counter component that:
- Displays a number with increment and decrement buttons
- Animates the number transition when changed
- Has a minimum and maximum value with appropriate visual feedback
- Includes a reset button to return to a default value
- Uses appropriate Compose animation APIs
- Follows Material Design principles for the buttons and layout
- Has proper state management

### Task 8: Image Carousel
**Problem Statement:**
Create a horizontal image carousel that:
- Displays 3-5 images (placeholders are fine)
- Allows swiping between images
- Shows a dot indicator for the current position
- Has navigation arrows on the sides for manual control
- Implements proper gesture handling for swipes
- Centers the current image with appropriate padding
- Uses Compose's gesture handling and animation capabilities

### Task 9: Toggle Switch with Theme Change
**Problem Statement:**
Implement a light/dark theme toggle that:
- Shows a switch UI element with appropriate icons
- Changes the app's theme when toggled
- Animates the transition between themes
- Affects multiple UI elements on the screen (text, backgrounds, etc.)
- Persists the selected theme state across composition
- Uses Material Theme properties appropriately
- Demonstrates understanding of theming in Compose

### Task 10: Weather Dashboard Card
**Problem Statement:**
Create a weather information card that:
- Shows current temperature with an appropriate weather icon
- Displays location name, weather condition text, and date
- Includes high and low temperatures for the day
- Has proper layout and alignment of all elements
- Uses appropriate typography hierarchy
- Implements a visually appealing design with colors matching the weather condition
- Takes weather data as parameters to make the component reusable
- Handles different weather conditions with different visual representations

## Intermediate Level (SDE-2)

### Task 1: Custom Calendar View with Event Display
**Problem Statement:**
Implement a custom calendar month view using Jetpack Compose that:
- Displays days of the month in a grid format with correct weekday alignment
- Highlights the current day with a distinct visual appearance
- Shows event indicators (small dots) on days that have associated events
- Handles month navigation with animations when moving between months
- Allows tapping on a day to display its events in an expandable section below
- Supports custom styling for different event types (e.g., work events, personal events)
- Implements proper state management and remembers the selected date
- Optimizes performance with appropriate Compose primitives and composition techniques

### Task 2: Advanced Data Chart with Interactive Elements
**Problem Statement:**
Create a line chart component that visualizes time-series data with the following features:
- Renders a smooth line chart with proper axis scaling
- Displays data points that show values on tap
- Supports pinch-to-zoom functionality to examine specific timeframes
- Implements horizontal scrolling for large datasets
- Shows a tooltip with detailed information when long-pressing a data point
- Includes a legend that allows toggling visibility of different data series
- Animates transitions when data changes or when filtering is applied
- Handles edge cases like empty datasets, single data points, and extreme values
- Optimizes rendering for performance with large datasets

### Task 3: Drag and Drop Kanban Board
**Problem Statement:**
Implement a simplified Kanban board with drag and drop functionality:
- Create three columns: "To Do", "In Progress", and "Done"
- Each column contains task cards that display a title and optional description
- Enable drag and drop of task cards between columns with smooth animations
- Show visual feedback during the drag operation (e.g., shadow, transparency)
- Update the data model when cards are moved between columns
- Support adding new tasks to any column
- Implement proper haptic feedback on drag operations
- Handle edge cases like empty columns and scrolling when columns exceed screen height
- Use composition and state hoisting correctly to manage state

### Task 4: Custom Bottom Sheet with Complex Behavior
**Problem Statement:**
Create a custom bottom sheet component with advanced functionality:
- Implement a bottom sheet that can be dragged to multiple snap points (e.g., collapsed, half-expanded, fully-expanded)
- Add custom spring-based physics for natural motion
- Handle nested scrolling behavior correctly when the sheet contains scrollable content
- Implement backdrop blur effect that increases with sheet expansion
- Show a drag handle with appropriate accessibility support
- Provide programmatic methods to control the sheet state
- Add haptic feedback at snap points
- Handle dismissal via swipe down or backdrop tap
- Ensure the component works with different content sizes and screen dimensions

### Task 5: Animated Multi-Step Form with Progress Indicator
**Problem Statement:**
Design and implement a multi-step form flow with:
- At least three form steps with different input fields and validation rules
- An animated progress indicator showing completion status
- Smooth transitions between steps with different animation patterns
- Form data persistence across steps
- Validation on each step before proceeding
- The ability to navigate back to previous steps while maintaining entered data
- Support for error states with appropriate feedback
- A summary screen before final submission
- State management that correctly handles the form's complete lifecycle
- Keyboard handling that adjusts the UI when the keyboard appears/disappears

### Task 6: E-commerce Product Card with Advanced Animations
**Problem Statement:**
Create a reusable product card component for an e-commerce app that:
- Displays product image, name, price, rating, and availability status
- Implements a "quick view" expansion with shared element transitions
- Animates between collapsed and expanded states showing additional product details
- Includes an "Add to Cart" button with loading and success states
- Shows an animated "heart" icon for wishlist functionality
- Implements image gallery navigation in expanded view
- Handles different product states (in stock, low stock, out of stock) with appropriate visual cues
- Uses Material 3 design principles with proper theming support
- Optimizes performance for list rendering scenarios

### Task 7: Interactive Data Filter System
**Problem Statement:**
Implement a complex filtering interface for a dataset that:
- Displays a set of filter chips for multiple categories (e.g., price range, ratings, categories)
- Shows selected filters with visual distinction
- Allows adding and removing filters with animated transitions
- Implements a collapsible/expandable filter panel
- Updates a result count in real-time as filters are applied
- Supports search within filtered results
- Provides a "clear all" option with appropriate confirmation
- Handles combinations of filters logically (AND/OR operations)
- Maintains filter state correctly during composition updates
- Uses Compose state management best practices

### Task 8: Custom Map Annotation Component
**Problem Statement:**
Create a custom map annotation system that:
- Displays location markers on a simulated map surface
- Shows clustered markers when multiple points are close together
- Implements custom callout bubbles that appear on marker tap
- Handles marker selection with appropriate visual feedback
- Animates between cluster and individual marker states when zooming
- Supports different marker types with distinct visual appearances
- Provides interactive elements within callouts (buttons, links)
- Maintains performance with a large number of markers
- Handles map panning and zooming interactions correctly
- Uses composition patterns for reusable marker and callout components

### Task 9: Animated Data Comparison Tool
**Problem Statement:**
Build an interactive comparison tool that:
- Displays two or more datasets side by side with synchronized scales
- Implements a draggable slider that reveals differences between datasets
- Shows animated transitions when switching between different comparison metrics
- Provides interactive tooltips with detailed information on data points
- Supports highlighting specific segments of data across all comparison views
- Includes a legend with toggle functionality
- Handles orientation changes gracefully
- Implements proper accessibility support for screen readers
- Uses advanced Compose animation APIs for coordinated animations
- Optimizes rendering performance for complex visualizations

### Task 10: Real-time Collaboration Indicator System
**Problem Statement:**
Design and implement a real-time collaboration indicator system that:
- Shows avatars of active users in a shared document or workspace
- Displays user cursors/selection indicators with name labels
- Animates cursor movements and highlights active editable regions
- Implements a typing indicator that shows when users are entering text
- Provides a notification system for user actions (joining, leaving, commenting)
- Handles multiple concurrent user activities with appropriate visual clarity
- Shows historical presence with fading indicators
- Manages the display of many simultaneous users without cluttering the UI
- Uses Compose effects and side effects correctly to simulate real-time updates
- Demonstrates understanding of complex state management across multiple sources

## Expert Level (SDE-3)

### Task 1: Custom Nested Navigation Architecture with State Preservation
**Problem Statement:**
Implement a sophisticated nested navigation system that:
- Creates a complex navigation graph with multiple levels (main tabs, detail flows, modal flows)
- Preserves UI state when navigating between destinations
- Handles deep linking to any screen in the hierarchy with proper argument parsing
- Manages back stack behavior with custom transitions between specific destinations
- Implements shared element transitions between routes when appropriate
- Provides an API for programmatic navigation from anywhere in the component tree
- Handles process death with complete state restoration
- Manages modal flows with proper lifecycle and state management
- Implements analytics hooks at navigation boundaries
- Optimizes for performance with proper composition scoping and key management
- Includes unit tests to verify navigation logic and state preservation

### Task 2: Fully Custom Gesture-Driven Interface
**Problem Statement:**
Create a canvas-based interface with complex gesture handling:
- Implement a drawing surface that supports multi-touch gestures
- Handle pinch-to-zoom, rotation, and panning of the canvas content
- Provide smooth freehand drawing with pressure sensitivity simulation
- Support object selection, movement, and transformation with handles
- Implement snapping behavior when moving objects near guidelines
- Handle gesture conflicts correctly (e.g., differentiating between drawing and selection)
- Add undo/redo functionality with proper state management
- Optimize rendering for complex drawings with potentially hundreds of elements
- Implement proper hit testing for object selection
- Handle edge cases like rapid gesture sequences and gesture cancellation
- Write custom modifier extensions that maintain composability

### Task 3: High-Performance Data Grid with Virtual Scrolling
**Problem Statement:**
Build a high-performance data grid component that:
- Handles extremely large datasets (10,000+ rows) with virtual rendering
- Supports fixed headers and footers with synchronized horizontal scrolling
- Implements column resizing, reordering, and sorting with correct state management
- Provides cell virtualization to efficiently render only visible cells
- Handles expandable/collapsible row groups with proper animations
- Supports cell editing with validation and optimistic updates
- Implements custom cell renderers based on data type
- Provides keyboard navigation and accessibility features
- Maintains 60fps scrolling performance under load
- Handles dynamic content height calculations efficiently
- Implements pagination with prefetching for smooth transitions

### Task 4: Advanced Animation Orchestration System
**Problem Statement:**
Design and implement an animation system that:
- Creates a complex multi-stage animation sequence with synchronized elements
- Implements physics-based animations with natural motion and bouncing effects
- Provides controls to pause, resume, rewind, and scrub through animations
- Demonstrates proper handling of AnimatedVisibility with custom transitions
- Implements path-based animations with timing functions
- Creates shared element transitions between different screens/states
- Builds a reusable animation library with composable API for different effects
- Handles animation state preservation during configuration changes
- Optimizes performance with proper keys and composition strategy
- Implements staggered animations for lists with variable timing
- Creates an API that allows defining animation choreography declaratively

### Task 5: Responsive Layout Engine with Design System Integration
**Problem Statement:**
Create a responsive layout engine that:
- Implements a constraint-based layout system similar to ConstraintLayout in Compose
- Supports different layout strategies based on screen size classes
- Provides breakpoint-based adaptations with smooth transitions between states
- Integrates with a design system to enforce spacing, typography, and color rules
- Implements an intrinsic measurement system for content-based sizing
- Handles RTL languages and different text directions properly
- Provides layout debugging tools and visual verification
- Creates reusable layout patterns (split views, master-detail, etc.)
- Supports dynamic content injection into predefined layout slots
- Handles complex nested scrolling scenarios correctly
- Optimizes layout measurement passes for performance

### Task 6: Real-time Collaborative Whiteboard
**Problem Statement:**
Implement a collaborative whiteboard application that:
- Renders a virtual whiteboard with drawing tools and object manipulation
- Simulates real-time syncing of actions between multiple users
- Shows user cursors and selections with appropriate attribution
- Handles conflict resolution when multiple users modify the same objects
- Implements operational transformation or a similar algorithm for consistency
- Provides presence indicators and action awareness (who's doing what)
- Optimizes for minimal recomposition during frequent updates
- Implements undo/redo that respects the collaborative nature of edits
- Creates an efficient serialization format for state transfer
- Handles latency simulation and error states gracefully
- Provides proper locking mechanisms for exclusive editing when needed

### Task 7: Custom Chart System with Interactive Analysis Tools
**Problem Statement:**
Create a sophisticated data visualization system that:
- Implements a pluggable architecture for different chart types (line, bar, scatter, etc.)
- Provides interactive tools for data analysis (trend lines, moving averages, etc.)
- Supports data highlighting and filtering through direct manipulation
- Implements zooming, panning, and data brushing with proper gesture handling
- Creates transitions between different visualization types with data continuity
- Handles real-time data updates with smooth animations
- Provides advanced tooltips with data comparisons and statistical analysis
- Implements proper axis scaling with various strategies (linear, log, time-based)
- Optimizes rendering performance for large datasets
- Creates a declarative API for chart configuration and styling
- Implements proper accessibility for screen readers to interpret data trends

### Task 8: Custom Accessibility Implementation for Complex UI
**Problem Statement:**
Design a complex UI component with comprehensive accessibility support:
- Implement a custom UI component (e.g., calendar scheduler, data table) with full semantics
- Create custom accessibility actions that map to component-specific functions
- Handle accessibility focus management with proper traversal order
- Implement hierarchical semantics for complex nested components
- Provide descriptive content descriptions that update with state changes
- Support screen reader announcements for dynamic content updates
- Implement proper keyboard navigation with visual focus indicators
- Create a testing framework for accessibility compliance
- Handle magnification and large text size gracefully
- Optimize the semantic tree for performance with large component trees
- Support different navigation modes (touch exploration, keyboard, switch control)

### Task 9: State Synchronization Framework for Distributed UI
**Problem Statement:**
Build a state management system for a complex distributed UI that:
- Creates a unidirectional data flow architecture with predictable updates
- Implements efficient state diffing to minimize recomposition
- Provides a time-travel debugging capability showing state transitions
- Handles asynchronous effects with proper cancellation and cleanup
- Implements optimistic UI updates with rollback capability on errors
- Creates a middleware system for cross-cutting concerns (logging, analytics)
- Manages derived state efficiently to avoid redundant calculations
- Provides tools for state persistence and hydration across sessions
- Handles complex form state with validation dependencies
- Implements proper error boundaries and recovery strategies
- Creates a testable architecture that supports dependency injection

### Task 10: Custom Design System Framework with Theme Variants
**Problem Statement:**
Create a comprehensive design system implementation that:
- Builds a token-based design system with semantic naming and organization
- Implements multiple theme variants (light, dark, high contrast, brand themes)
- Creates dynamic color palettes derived from base colors with proper contrast checking
- Supports animation presets that maintain consistency across the application
- Implements a component variant system with proper type safety
- Provides theme switching with smooth transitions between themes
- Creates developer tooling for theme preview and validation
- Handles custom shapes and elevation consistently across components
- Implements proper theming for custom canvas-based components
- Provides extension points for app-specific theme customization
- Creates an API that enforces design system constraints while remaining flexible

## Evaluation Criteria

### Beginner Level (SDE-1)
- Basic understanding of Jetpack Compose fundamentals
- Proper implementation of state management
- Correct use of layout composables
- Understanding of basic animations and transitions
- Proper organization of composable functions
- Following Material Design guidelines
- Component reusability and parameterization
- Clean and maintainable code structure

### Intermediate Level (SDE-2)
- Advanced state management techniques
- Custom gesture handling and complex interactions
- Performance optimization strategies
- Handling of edge cases and error states
- Creative use of animations and transitions
- Building reusable component systems
- Understanding of composition patterns
- Integration with data models and state holders
- Proper lifecycle management

### Expert Level (SDE-3)
- Architectural design skills for complex UI systems
- High-performance rendering and optimization
- Advanced state management architectures
- Creation of developer-friendly APIs and abstractions
- Handling of complex async workflows and side effects
- Deep knowledge of Compose internals and optimization
- Accessibility implementation for complex UIs
- Custom layout algorithms and rendering
- Extensible design system implementation
- Testing strategies for complex UI components