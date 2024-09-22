# iPod Menu Clone using React.js

This project is a replica of the classic iPod interface, built using React.js, featuring an interactive circular menu for navigation.

## Features

- **Main Menu**: Includes options like "Settings", "Games", "Music", and "Coverflow". The menu displays these options on a scrollable interface.
  
- **Circular Navigation Wheel**: Implemented the iconic iPod click-wheel interaction. Users can click and hold on the circular wheel and drag it in a circular motion to scroll through the menu options. The currently selected option is highlighted with an "active" class.

- **Menu Navigation**:
  - Clicking the "OK" button opens the selected item’s screen (e.g., Settings, Games, Music).
  - Clicking the "Menu" button returns to the main menu from any submenu or screen.

- **Submenus**: Under the "Music" option, there are submenus like "All Songs", "Artists", etc. Similar navigation applies here.

- **First Item Selected**: By default, the first item selected on the side menu is "Coverflow" when the app starts.

## Key Components

- **SideMenu Component**: The main menu that displays various options and handles the navigation logic.
  
- **Circular Control**: Implements the logic for click and drag functionality, ensuring smooth scrolling of the menu items.

## Technologies Used

- React.js
- CSS for styling and animations

## How to Run

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to view the project in action.

Feel free to explore the code and contribute!
