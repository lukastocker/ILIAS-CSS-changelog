![CSS changes 28.07 - 03.08.25](../../../_imgs/entries/2025/07-July/header_changelog-entry_july-w5.png)

# Week 5 of July

## Inactive Buttons in Dropdown

`medium impact` `UI framework` `broke mental model`

[→ Mantis Issue](https://mantis.ilias.de/view.php?id=45480)

### Issue

Buttons with unavailable actions inside a UI component dropdown look exactly like buttons with available actions.

### Changes

![inactive-buttons-in-dropdowns_comparison.png](../../../_imgs/entries/2025/07-July/inactive-buttons-in-dropdowns_comparison.png)

UI Component Dropdown

* Fix: Using the disabled background color for the entire menu item
* Fix: As all other unavailable buttons, cursor symbol is now set to "not-allowed"
* Maintenance: Code structure tweaks to stretch buttons across menu
* Maintenance: Ensure buttons and links in dropdowns have the same height

### Impact

* for system styles: check in Kitchen Sink if your skin visibly marks unavailable actions in Dropdowns

### Outlook

We should consider adding a menu tool/pattern to derive drodpown, drilldown, tree,... buttons from.
