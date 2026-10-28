PARALLEL — COMPARE WEBSITES AND MOCKUPS

Live site: https://parallel-compare.onrender.com/

This address now opens the server-browser version:
https://parallel-browser-l7t7.onrender.com/
Its current source is https://github.com/loca555/parallel-browser.
The static index.html in this repository is the migration entry point.
The portable copy below remains an offline tool for images and standalone HTML;
live website browser panels require the server-browser version.

Two empty panels open by default. Add or remove panels as needed, up to eight.
Only open panels use space. Drag a divider or use Equal widths to rebalance.

Load HTTPS websites, images or self-contained HTML files. Files stay in the
browser. Embedded JavaScript runs in an isolated preview. External resources
are blocked. A standalone HTML must include its CSS, JavaScript, images and
fonts; index.html alone cannot read adjacent files from your computer.
If a file needs separate assets, Parallel explains this instead of showing a
broken page. Use a self-contained export or the published website URL.
Images and local HTML can scroll together; external websites scroll independently.
Some websites block iframe embedding. Use the open-in-new-tab button or a screenshot.

Deployment: Render Static Site, branch main, build command: echo ready,
publish directory: dist. No dependencies, backend or environment variables needed.
For this public Git repository connection, deploy updates from the Render Dashboard.

Open dist/portable.html or Parallel.html for a self-contained offline copy.
Font licenses are included in dist/assets/.
