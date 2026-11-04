## 2024-11-04 - Add ARIA Labels to Tree Toggle Buttons
**Learning:** Icon-only expand/collapse buttons on tree views (like in StoryModeTreeCard and GenreTreeItem) can easily be overlooked for accessibility. Without `aria-label` and `aria-expanded`, screen reader users have no context for what the button does or its current state.
**Action:** When implementing collapsible components or tree nodes, always ensure toggle buttons have descriptive `aria-label`s and use `aria-expanded` to communicate their state.
