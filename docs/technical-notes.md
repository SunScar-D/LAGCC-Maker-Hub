# Technical Notes (Week 1)

## Sites reviewed

### Devpost (devpost.com/software)
- **Card:** image or large title on top, then title, short description and team. Shows likes, comments and a "Winner" tag.
- **Modal:** none. Clicking opens a separate page.
- **Filters/search:** dropdown (staff picks, winners only, demo videos) plus one search box for users, tags and keywords.
- **Click behavior:** opens its own page with the description, team, how it works, challenges and comments.
- **Empty search:** says nothing found, then shows featured projects below.
- **Phone:** one card at a time, scroll down.

### Behance (behance.net)
- **Card:** mostly visuals, little text. Name or short description, likes, views, save button and creative-field label.
- **Modal:** yes. Clicking a card opens the project in a popup over the gallery. Closes with the X button and Esc, but not by clicking outside.
- **Filters/search:** creative field, location, tools, views and date.
- **Click behavior:** opens the modal, mostly images and videos.
- **Empty search:** says no results and suggests keywords to try.
- **Phone:** one card at a time, scroll down.

### Dribbble (dribbble.com)
- **Card:** mostly visuals. Brand logo and team name.
- **Modal:** yes, same as Behance. Closes with the X button and Esc, but not by clicking outside.
- **Filters/search:** keyword search and popularity.
- **Click behavior:** opens the modal with a short description and contact info.
- **Empty search:** just says no results found.
- **Phone:** one card at a time, scroll down.

## Main finding
Behance and Dribbble use a **modal**. Devpost opens a separate page. Our guide says to use a modal, which matches the majority, and it keeps users on the gallery with their filters.

## Patterns I'll use
- **Card:** thumbnail, title, short description, tags.
- **Filters:** category filter plus text search, with a reset button.
- **Detail view:** modal that closes with the X button and Esc (both sites do this). Click-outside is optional, since neither site supports it.
- **Empty search:** "No projects found" message with a hint and a reset button. Devpost's featured projects and Behance's keyword tips are extras.
- **Phone:** single-column layout, one card per row, vertical scroll.


