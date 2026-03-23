# Quantity Measurement App

A web-based system for converting, comparing, and performing arithmetic on quantities (Length, Weight, Temperature, Volume) with a modern UI and persistent history.

---

## Features

- Convert between units with accurate formulas
- Compare values across different units
- Perform arithmetic operations (+, −, ×, ÷) on quantities
- View and search calculation history
- Responsive, user-friendly interface

---

## Project Structure

- **db.json** — JSON server database for units and history
- **js/api.js** — Handles all async API calls (fetch units, conversions, history)
- **js/conversion.js** — Pure functions for conversion, comparison, arithmetic
- **js/ui.js** — UI utilities: dropdowns, result display, history rendering
- **js/app.js** — Main app logic: state, event handlers, calculation workflow
- **css/style.css** — Modern, responsive styles
- **html/quantityapp.html** — Main app UI
- **html/index.html** — Entry point (loads app shell)

---

#### UC-JS-01: Define and seed the JSON server database with units, conversions, and history collections.
#### UC-JS-02: Initialise the app, load default data, and attach all event listeners on page load.
#### UC-JS-03: Fetch available units for a selected measurement type from the backend.
#### UC-JS-04: Retrieve the conversion factor or formula for a specific unit pair.
#### UC-JS-05: Save each completed calculation as a record in the history collection.
#### UC-JS-06: Load and display all calculation history records, sorted by newest first.
#### UC-JS-07: Apply a conversion using either a numeric factor or a formula string.
#### UC-JS-08: Compare two normalized values and return a human-readable comparison.
#### UC-JS-09: Perform arithmetic operations (+, −, ×, ÷) between two normalized values.
#### UC-JS-10: Populate a dropdown menu with unit options after fetching units.
#### UC-JS-11: Set the active visual state for type, action, or operator buttons.
#### UC-JS-12: Display the calculation result with appropriate formatting and animation.
#### UC-JS-13: Show or hide the operator row based on the selected action mode.
#### UC-JS-14: Render the calculation history list in the UI, showing all records.
#### UC-JS-15: Handle type card clicks to update state, reload units, and reset results.
#### UC-JS-16: Handle action tab clicks to switch modes, toggle operator row, and clear results.
#### UC-JS-17: Execute the appropriate calculation and update the result and history on input change.

