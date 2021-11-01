---
weight: 3220
title: "Javascript helpers functions"
description: "How to use javascript helpers functions?"
titleIcon: "fab fa-js-square"
categories: ["Functionalities"]
---

# Description
---

In order to ease the use of the theme, some javascript functions defined in the file **assets/js/theme/modules/helpers.js** are provided.
These functions are defined globally using the file **assets/js/theme/modules/helpersGlobal.js** and thus can be called from every scope.

## JavaScript helper functions
---

| Code | Description |
| ---- | ----------- |
| closeModals(modal); |{{< md >}}
Function managing modal closing:
* If filled in, only the modal set as input is closed
* If no input, all modals are closed
{{< /md >}}|
| disableSmoothScroll(); |{{< md >}}
Fonction deactivating smooth scrolling on main content.
{{< /md >}}|
| enableSmoothScroll(); |{{< md >}}
Fonction activating smooth scrolling on main content.
{{< /md >}}|
| getFirstVisibleElement(selector); |{{< md >}}
Function getting the first visible element from a CSS selector:
* selector
    * [CSS selector](https://developer.mozilla.org/docs/Web/CSS/CSS_Selectors)
{{< /md >}}|
| manageDefaultCollapsibleSidebar(); |{{< md >}}
Function managing the default behavior of the sidebar:
* If the window is greater than or equal to 1024 pixels wide, sidebar is uncollapsed
* If the window is less than 1024 pixels wide, sidebar is collapsed
{{< /md >}}|
| toggleExtendMenu(force); |{{< md >}}
Function managing the extend menu of the navigation bar (only if it is displayed):
* force
    * true: the extend menu is displayed
    * false: the extend menu is hidden
{{< /md >}}|
| toggleSidebar(force, noTransition); |{{< md >}}
Function managing the sidebar behavior:
* force
    * true: the sidebar is uncollapsed
    * false: the sidebar is collapsed
* noTransition
    * true: turn off menu transition animation
    * false: turn on menu transition animation (default behavior)
{{< /md >}}|
| toggleSidebarEntry(entry, force); |{{< md >}}
Function managing the sidebar entry:
* entry
    * menu entry that can expand or shrink its elements (\<a> elements containing *is-icon-expandable* class)
* force
    * true: entry is expanded
    * false: entry is shrinked
{{< /md >}}|
| toggleSidebarEntries(force); |{{< md >}}
Function managing the sidebar entries:
* force
    * true: all entries are expanded
    * false: all entries are shrinked
{{< /md >}}|