# MAST5112-PART3
# Ganyth Eatery App - Changelog

## Version 1.0 (Initial Setup)
- Created a new React Native project using TypeScript.
- Installed **React Navigation** and set up a stack navigator.
- Created the initial screens: **Home**, **Starters**, **Mains**, and **Desserts**.
- Implemented `MenuItem` interface for type-safe menu data.

## Version 1.1 (Menu Display & Featured Switch)
- Displayed menu items with **FlatList**, showing name, description, price, and image.
- Added a **Switch** to toggle featured items for each menu item.
- Styled menu cards using `StyleSheet`.

## Version 1.2 (Navigation Improvements)
- Fixed navigation between **Home** and menu screens.
- Added buttons on the Home screen to navigate to **Starters**, **Mains**, and **Desserts** screens.

## Version 1.3 (Final POE Requirements)
- **Reorganized app structure**:
  - Home screen now displays **average prices** per course.
  - Created **Manage Menu** screen for the chef to add/remove menu items.
  - Created **Filter Menu** screen for guests to filter by course.
- Updated state management to keep **menu items in arrays** so changes persist across screens.
- Updated navigation to include **Home**, **Manage Menu**, and **Filter Menu**.

## Version 1.4 (Bug Fixes & Enhancements)
- Fixed **TypeScript navigation typing** issues.
- Ensured **image URLs** render properly.
- Cleaned up UI for consistent styling across screens.
- Added average price calculation logic for each course on the Home screen.

