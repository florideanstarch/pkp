---
title: Test - UDL figure embed
authors: Satya
---

Throwaway page to test embedding. Delete me once the flow is verified.

## 1. External: UDL interactive figures (live app from udlbook.github.io)

The whole app is embedded, it opens on Figure 2.1 and the figure is chosen from the sidebar inside the frame (the app keeps selection in its own state, so a single figure cannot be linked to).

<iframe
    src="https://udlbook.github.io/udlfigures/"
    style="border: none; display: block; margin: auto; width: 100%; height: 700px;">
</iframe>

## 2. Static: plotly HTML from `static/ml-dl/` (same path as the real notes)

A ReLU, transparent background so it should look right in both light and dark mode:

<iframe
    src="/static/ml-dl/test-relu.html"
    sandbox="allow-scripts allow-same-origin"
    style="border: none; display: block; margin: auto; width: 70%; height: 320px;">
</iframe>
