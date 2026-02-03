# TapTable - Tabbed Workspace Plugin

![TapTable](https://creator.ianstudios.id/storage/docs-images/01KFCSRW46MXDVYX6M8MWG6XKA.png)

**The Ultimate Menu Builders for Filament.**
Turn messy sidebars into sleek, app-like workstations. Mix Resources, Charts, Livewire Forms, and Blade Views in a single, state-isolated page.

---

## 🚀 Description

**TapTable** is a high-performance architectural plugin for Filament v3 that allows developers to group multiple unrelated components into a single "Tabbed Workspace".

Unlike standard tabs, TapTable offers **True State Isolation**. Search, pagination, and filters in one tab do not conflict with others. It supports a "Polyglot" architecture, meaning you can render a **Resource Table** next to a **Livewire Chart** or a **Custom Setting Form** without writing complex boilerplate.

## ✨ Key Features

* **Universal Container:** Render Resources, Widgets, Livewire Components, and Static Views in one place.
* **State Isolation:** Built-in `queryStringIdentifier` management ensures search/filter query strings never collide.
* **Ghost Resources:** Easily hide Resources from the main sidebar (`showInNavigation => false`) while keeping them accessible via tabs.
* **Smart Action Injection:** Automatically inherits standard Filament actions (Create, Edit, Delete) within the tab context.
* **Dynamic Badges:** Support for real-time counts, status colors, and dynamic queries in tab labels.
* **Responsive Tile Design:** Compact, mobile-friendly tab navigation that maximizes screen real estate.


View documentation here [TapTable Full Documentation](https://creator.ianstudios.id/documentation/taptable-tabbed-workspace-plugin)