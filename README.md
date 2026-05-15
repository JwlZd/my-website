My Cookbook Website 🍪🍓🥤

A colorful interactive cookbook website made with HTML, Tailwind CSS, and JavaScript.

Features
Sweet, Savory, and Drink recipe pages
Clickable recipe images
Popup recipe modals (no page switching)
Custom SpongeBob + Spatula cursors
Hover animations
Responsive layout
Google Fonts styling
Recipe navigation buttons
Languages Used
HTML
CSS
JavaScript
Tailwind CSS
Pages
index.html → Home page
Sweet.html → Dessert recipes
Savory.html → Savory food recipes
Drinks.html → Drink recipes
How It Works

Each recipe image has an onclick function:

onclick="openModal('cookie1')"

When clicked:

JavaScript finds the recipe data
Opens the popup modal
Displays the recipe title + instructions
Example Recipe Object
cookie1: {
  title: "Chocolate Chip Cookies",
  text: `1/2 cup butter
1 egg
1 cup flour

Bake at 175°C`
}
Popup Modal System

The modal is hidden by default:

<div id="modal" class="hidden">

JavaScript removes the hidden class when a recipe is clicked.

Custom Cursor
*{
  cursor: url("Spatula.png") 16 16, auto;
}

button,
a,
img {
  cursor: url("SpongeBob.png") 16 16, pointer;
}
Font Used

Google Font:

Pacifico
Tailwind CSS

Tailwind was used for:

colors
spacing
rounded corners
shadows
hover effects
responsive flex layouts

Example:

class="w-60 h-60 object-cover rounded-2xl shadow-lg hover:scale-105 transition duration-300"
Future Improvements
Add search bar
Add random recipe button
Add background music toggle
Add recipe categories
Add recipe ratings
Add dark mode
Add favorites system
Add cooking timer
