# Sitemap Visualization Tool

This tool provides an interactive way to visualize your XML sitemaps using various D3.js powered layouts. It allows for easy exploration and analysis of your website's structure.

## Features

*   **Interactive Sitemap Visualization:**
    *   **Input:** Easily load your `sitemap.xml` files via drag-and-drop or file upload.
    *   **Multiple Layouts:** Choose from several D3.js visualization types to best represent your sitemap:
        *   **Collapsible Tree:** A classic hierarchical tree view with expand/collapse functionality.
        *   **Radial Tidy Tree:** A compact, circular representation of your sitemap.
        *   **Radial Cluster:** Another circular layout, useful for showing clustering of pages.
        *   **Cascaded Treemap:** A space-filling visualization where rectangles are sized and colored by hierarchy.
        *   **Indented Tree:** A simple, list-like hierarchical view.
    *   **Interactive Exploration:** Pan, zoom, and expand/collapse nodes to navigate large sitemaps.
*   **Search Functionality:** Quickly find specific pages or patterns within your visualized sitemap.
*   **Link Mode:** Hold `Ctrl` or `Cmd` and click on any node to open the corresponding URL in a new tab.
*   **Export Options:**
    *   **SVG Export:** Download your current visualization as a high-quality, scalable vector graphic (SVG).
    *   **PNG Export:** Save your visualization as a portable network graphic (PNG) for easy sharing and inclusion in reports.