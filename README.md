# Sitemap Visualization Tool

This tool provides an interactive way to visualize your XML sitemaps using various D3.js visualizations. It allows for simple exploration and analysis of your website's structure.

## Features

*   **Interactive Sitemap Visualization:**
    *   **Input:** Load your `sitemap.xml` file via browser or drag-and-drop.
    *   **Multiple Layouts:** Choose from several D3.js visualization types to best represent your sitemap:
        *   **Collapsible Tree:** A classic hierarchical tree view with expand/collapse functionality.
        *   **Radial Tidy Tree:** A compact, circular representation of your sitemap.
        *   **Radial Cluster:** Another circular layout, useful for showing clustering of pages.
        *   **Cascaded Treemap:** A space-filling visualization where rectangles are sized and colored by hierarchy, with additional aspect ratio controls.
        *   **Indented Tree:** A simple, list-like hierarchical view.
    *   **Interactive Exploration:** Pan, zoom, and expand/collapse nodes to navigate large sitemaps.
*   **Search:** Find specific pages or patterns within your visualized sitemap.
*   **Link Mode:** Hold `Ctrl` or `Cmd` and click on any node to open the corresponding URL in a new tab.
*   **Export:**
    Save as a PNG or SVG
    (note that the PNG will export with a default font, not the font you see on the canvas).