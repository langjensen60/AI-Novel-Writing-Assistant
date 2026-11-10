## 2026-11-10 - Tree View Toggle Button Accessibility
**Learning:** For tree view components (like `StoryModeTreeCard` and `GenreTreeItem`), the expand/collapse toggle button must have both `aria-expanded` indicating the current state (or `undefined` if no children) and `aria-label` (e.g., "展开" or "折叠") describing the action.
**Action:** Always ensure icon-only toggle buttons in collapsible components include both `aria-expanded` and `aria-label` attributes to support screen readers properly.
