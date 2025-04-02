# Checklist Application

A modern, responsive web application for managing multiple checklists with a clean and intuitive interface.

## Features

- **Multiple Checklists**: Create and manage multiple checklists
- **Persistent Storage**: All data is saved in the browser's localStorage
- **Item Management**:
  - Add new items
  - Mark items as complete/incomplete
  - Delete items
  - Automatic reordering (unchecked items stay at the top)
- **Responsive Design**: Works well on both desktop and mobile devices
- **Modern UI**: Clean, Material Design-inspired interface
- **Keyboard Support**: Quick item creation with Enter key

## Usage

### Creating a New Checklist
1. Click on the checklist title in the menu bar
2. Select "Create New Checklist" from the dropdown
3. Enter a title for your new checklist

### Managing Items
- **Add Item**: Click the + button at the bottom of the page
- **Complete Item**: Click the checkbox next to an item
- **Delete Item**: Click the trash icon next to an item
- **Edit Item**: Currently not supported (items must be deleted and recreated)

### Switching Between Checklists
1. Click on the current checklist title in the menu bar
2. Select the desired checklist from the dropdown

## Technical Details

- Built with vanilla JavaScript
- Uses MDB (Material Design for Bootstrap) for UI components
- No backend required - all data is stored locally
- Responsive design with a maximum width of 900px
- Mobile-friendly interface

## Browser Support

The application works in all modern browsers that support:
- localStorage
- ES6 JavaScript features
- CSS Flexbox

## Future Improvements

- Item editing functionality
- Drag and drop reordering
- Checklist sharing
- Export/import functionality
- Dark mode support 