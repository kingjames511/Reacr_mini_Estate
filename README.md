# Property Listing Application

A React application that displays property listings with hierarchical navigation through properties, floors, and apartment layouts.

## Features

- View property listings with images and details
- Navigate through floors of each property
- View different apartment layouts for each floor
- See detailed information about specific layouts
- Responsive design for all screen sizes

## Installation

1. Clone the repository:
   git clone https://github.com/yourusername/property-listing-app.git# Reacr_mini_Estate
2. installation
   cd property-listing-app
   npm install
3. start the server
   npm run dev

DATA STRUCTURES
The application uses three main data structures:

PROPERTIES
Contains basic information about each property:

ID, title, location, price
Beds, baths, square footage
Image, agent information

FLOORS

Organized by property ID, contains:
Floor number
PrIce, available units
Floor image

LAYOUTS
Organized by property-floor combinations (e.g., "2-1" for property 2, floor 1), contains:
Layout type (Studio, 1-Bedroom, etc.)
Area, room count, bathroom count
Features list
Thumbnail and large images

COMPONENTS
PropertyCard: Displays property information
FloorCard: Displays floor information
LayoutCard: Displays apartment layout information
LayoutDetail: Detailed view of a specific layout

STATE MANAGEMENT
The application uses React's useState to manage:
Current view state
Selected propertY
Selected floor
Selected layout
Custom Hooks
None currently, but the state management could be refactored into custom hooks for better organization in future versions.

DEPENDENCIES

React
Lucide React (for icons)
Tailwind CSS (for styling)

FUTURE IMPROVEMENTS

Add search/filter functionality
Implement backend API integration
Add user authentication
Enable favoriting properties
Add map integration for property locations
