# Project Blueprint

## Overview

This project is a personal link-sharing page, similar to Linktree, for a VTuber named RyumiiVT. It features a futuristic, "Cyber" aesthetic with animated, interactive elements.

---

## Version 5.1: Centering Bug Fix

*   **Layout:** Corrected a critical regression bug that broke the application's centered layout. The flexbox properties (`display: flex`, `justify-content: center`, `align-items: center`) were restored to the main `body` tag in `src/layouts/Layout.astro`.
*   **Bug Resolution:** This fix ensures that the main content is once again properly centered horizontally and vertically on all screen sizes, restoring the intended design.

---

## Version 5.0 (Legacy): Luminous Neural Network Background (with layout issues)

*   **Aesthetic:** Introduced a sophisticated and interactive "Luminous Neural Network" background.
*   **Issues:** In the process of implementing the new background, the CSS rules responsible for centering the page content were accidentally removed, causing a major layout regression.

---

## Version 4.1 (Legacy): Brand-Aware Cybernetic Scan

*   **Aesthetic:** A refined "Cybernetic Scan" effect for the social media buttons with brand-specific colors.

---

## Current Plan: Fix Centering Regression

**Goal:** Restore the correct, centered layout for all content on the page.

**Steps:**

1.  **Identify the Error:** Recognized that the CSS centering rules were mistakenly removed from the `body` element in `src/layouts/Layout.astro` during the previous update.
2.  **Restore Flexbox Properties:** Re-applied `display: flex`, `justify-content: center`, and `align-items: center` to the `body` style rules.
3.  **Update `blueprint.md`:** Documented the bug and its resolution as Version 5.1 to maintain an accurate project history.
