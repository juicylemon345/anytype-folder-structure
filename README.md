# Anytype File-Like Structure Guide

Welcome! This repository provides a practical, step-by-step guide on how to set up a traditional folder and directory structure inside **Anytype**, despite its native graph-based object model.

## 📂 The Core Strategy

Unlike traditional note-taking apps that rely on rigid parent-child folder trees, Anytype uses local-first objects. To mimic a classic file explorer, you can combine **Sidebar Widgets (Hierarchical View)**, **Collections**, and **Page Links**.

### Step 1: The Sidebar Hierarchical Widget (Nested Folders)
1. Create a master Object with a **Page format** and name it something like **"Root Directory"** or **"Workspace"**.
2. Inside that page, link your sub-pages or sub-folders using `/link` or the `@` symbol.
3. Pin this master page to your sidebar as a **Widget**.
4. Right-click the sidebar widget and select **Hierarchical Structure** from the view settings to create an expandable, nested tree view.

### Step 2: Collections (Dynamic Containers)
1. Create a **Collection** via the sidebar dropdown.
2. Manually drag and drop files into it, or bulk-import desktop files and folders directly.
3. Pin the Collection to your sidebar for quick, folder-like access.

---

## 🛠️ How to Solve Common Friction Points

* **Problem:** *You can't drag-and-drop pages into nested sub-folders directly in the default sidebar tree.*
  * **Solution:** Use **Sidebar Widgets with Hierarchical Structure** enabled, and map your nesting by adding manual page links inside the master parent pages.
* **Problem:** *Files feel lost or buried in deep sub-folders.*
  * **Solution:** Leverage **Sets and Queries**. Instead of deep manual nesting, tag your objects with specific properties (e.g., `Category: Finance`) and create filtered list views to pull them up instantly.
