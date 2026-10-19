NMC vs LFP Battery Chemistry Explorer

QUICK PUBLISH WITH GITHUB PAGES

1. Create a new repository on GitHub.
2. Extract this package and upload index.html, en.html, and ru.html to the repository's top level.
3. In the repository, open Settings > Pages.
4. Under Build and deployment, select "Deploy from a branch".
5. Select the main branch and the /(root) folder, then Save.
6. Open the published Pages URL shown in Settings > Pages.

The page is a standalone HTML file and needs no build step or dependencies.
Use the fullscreen button on the page to hide browser chrome. You can also
use the browser's fullscreen shortcut (Control+Command+F in many Mac browsers).
The index page provides an in-page English/Russian switch. Keep all three HTML
files together at the top level of your GitHub repository so both languages
work after publishing. The switch stays in the same tab and carries the
current chart and configuration inputs across languages.
In the module builder, set a fixed total cell count and a series count; the
parallel count adjusts automatically. For a uniform module layout, the total
must divide evenly by the series count.
The battery builder uses that module design as a template. Set series and
parallel module counts directly, or enter target nominal voltage and energy
and use Auto-fit to find whole-module counts that minimize the combined
relative difference from both targets.
GitHub's file preview does not run standalone HTML as a website; GitHub Pages
publishes it as a web page. The layout is responsive and has a fullscreen
button; browser support and settings may affect fullscreen behavior.
