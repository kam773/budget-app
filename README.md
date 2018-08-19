# Budget-app

https://kam773.github.io/budget-app/

# The Project

Application allows you to manage your budget, store list of expenses as well as income.

# The Logic

Data object stores all expenses and income. App is build using JavaScript module pattern. App consist of 3 modules connected each other. UI  controller consist all logic which handles DOM manipulation. Budget controller consist logic which stores all expenses and income in data object with set of helper methods used to calculate, update budget and percentages. Last module - general app controller connect UI controller with budget controller and manages all application logic to work together.
