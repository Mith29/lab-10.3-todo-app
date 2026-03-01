                          Todo App


This application is built using React Context API for state management. The app is divided into three main contexts: TodoContext (for managing todos), FilterContext (for controlling filters), and ThemeContext (for light/dark mode). The app also saves todos and theme settings in localStorage, so data remains even after refreshing the page. 


The app allows users to add, edit, delete, and mark todos as completed. Users can also clear all completed tasks. The Todo list can be filtered to show All, Active, or Completed items using the FilterContext. The ThemeContext allows switching between light and dark themes, and the UI updates visually based on the selected theme. Both the todo list and theme preference are automatically saved to localStorage and restored when the app reloads. All state and actions are managed through Context providers, keeping components clean and organized.