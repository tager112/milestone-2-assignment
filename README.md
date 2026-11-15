Tarsh Branch - IT Portfolio (Milestone 3)

Live Site: https://tager112.github.io/milestone-2-assignment/

Accessibility fixes

I tested all three pages on WAVE and fixed the issues so every page has 0 errors.

Color contrast - I checked my colors on the WebAIM Contrast Checker and used dark purple #6a0dad on white #ffffff for my headings and buttons instead of light purple, so people with low vision can read the text easily.
Heading order - I set up my headings in order from h1, h2, and h3 without skipping levels, so screen reader users can scan my page outline without getting confused.
Link text and keyboard focus - I used clear words on my links like "View My Projects" instead of "click here" and added focus-visible outlines, so anyone using the Tab key knows where they are on the page.
Contact form labels and errors - I connected every <label> to its <input> box, wrapped my radio buttons in a <fieldset> and <legend>, and added error messages right under the boxes instead of using pop-up alerts so screen readers can read them out loud.

Design choices

I saved my black, purple, and white color scheme as :root variables at the top of style.css to keep all three pages matching, and used two Gestalt principles:

Proximity: Each project title and form label sits 8px from its text or input box while separate cards and form sections have 24px of space between them, so the brain sees which items belong together.
Similarity: Every content box and project card shares the same purple top border, white background, and rounded corners, and my buttons look the same on every page so the user knows how they work.
