# Tailwind CSS Styles Not Applying

This repository demonstrates a common but elusive issue in Tailwind CSS: styles failing to apply despite seemingly correct setup. The problem lies in ensuring proper inclusion of the generated CSS file and that Tailwind's purge mechanism is working as expected.  The `bug.html` file shows the initial problematic code; `bugSolution.html` provides the solution.

**Problem:** Styles defined in Tailwind directives are not applied to elements.

**Solution:** Ensure correct CSS file import and appropriate configuration of the purge option in `tailwind.config.js` (if using PurgeCSS).

To run the example:
1. Clone the repository.
2. Run `npm install` (if using npm, or yarn if using yarn)
3. Open `bug.html` and `bugSolution.html` in your browser to observe the differences.