# MAST5112 Final POE - ST10524342
Student: Umile - ST10524342
Snack: https://snack.expo.dev/@umilerr/your-choice

## Changes Since Part 2 - Change Log

### 1. Manage Menu Items (25 Marks)
- Added editingId state to track edit
- Added handleEdit() - loads item into form for editing
- Added handleDelete() - deletes item immediately
- handleSave() now does both Add and Update

### 2. Search and Filter (20 Marks)
- Added searchQuery state + filterCourse state
- Added filteredItems logic: search by name + filter by course
- Added search bar and filter buttons (All/Starter/Main/Dessert)
- Added Clear button to show all items

### 3. Menu Statistics (20 Marks)
- Added totalItems = menuItems.length
- Added averagePrice = sum / total
- Added starterCount, mainCount, dessertCount
- Displayed in statsBox that updates immediately

### 4. Enhance Application (20 Marks) - Refactoring
- Created reusable component: CourseButton (was repeated 3 times)
- Created reusable functions: handleSave(), clearForm()
- Improved code organization and meaningful names
- Created distinct sections: stats, form, search, list

### 5. User Experience (10 Marks)
- Validation for empty name/price and invalid price
- Visual feedback: active buttons highlighted
- Consistent styling throughout
- Alerts for errors

Video: [YOUR YOUTUBE LINK HERE - UNLISTED]
