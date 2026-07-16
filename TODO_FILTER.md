# Filter Button Task

## Goal
Update the Home screen filter button so it:
1) Lets the user pick categories (UI).
2) Filters the feed to show only categories the user selected in their Profile (interests).

## Step 1: Repo understanding
- [ ] Locate the current filter button behavior in dis.html (Home header).
- [ ] Locate existing category/interests filtering logic in Home.

## Step 2: Design
- [ ] Decide how the filter picker UI will work (modal or expanded panel).
- [ ] Use profile interests as the selectable categories.

## Step 3: Implementation
- [ ] Replace the current filter button toggle with open/close category picker.
- [ ] Add state for selected categories from the picker.
- [ ] Apply filtering: show offers only where offer.category is within selected categories.
- [ ] Ensure search continues to work alongside category filtering.

## Step 4: Profile interaction
- [ ] Ensure when user updates interests in Profile, the filter UI reflects those interests (and feed updates).

## Step 5: Validate
- [ ] Verify:
  - Filter picker opens/closes.
  - Selecting categories updates feed.
  - Only profile-selected categories show.
  - Search + category filters combine correctly.

