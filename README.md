# MOOgle Farm Tracker 

## Overview
This is a single-page application to manage a small farm's Gelbvieh and Balancer cattle. It tracks animal information, medications, overdue medications, and allows import/export of data.

## Features
- Track cows and bulls by Tag # and Tattoo #
- Record animal details including breed, type, location, parentage, udder scores, calving ease, docility, DOB, and DOD
- Add, edit, delete animal records
- Track medication administration with date, type, quantity, next due
- Administered medications are excluded from overdue highlights
- Overdue medications highlighted in red and listed in a separate table
- Search animals by Tag or Tattoo
- Import/Export JSON data
- Dynamic dropdowns for breed, scores, and traits

## Usage
1. Open `index.html` in a web browser
2. Edit farm info using the button at the top
3. Add or edit animal records using the form
4. Administer medications by checking the box in the medications table
5. Use the search fields to find animals
6. Export data for backup or import new data to merge records

## Notes
- Overdue medications include any due today
- Administered medications are grayed out
- Age is calculated from Date of Birth automatically
