# Features Details

> **[日本語](features.md)**

This document provides detailed information about each feature of Backlog Usability Enhance.

## Table of Contents

- [Board Accordion Feature](#board-accordion-feature)
- [Shortcut Key Display Feature](#shortcut-key-display-feature)
- [Issue Pending Feature](#issue-pending-feature)
- [PR Format Auto-Insert Feature](#pr-format-auto-insert-feature)
- [Issue Comment URL Copy Feature](#issue-comment-url-copy-feature)

---

## Board Accordion Feature

### Overview

Individual collapse/expand of status columns to focus only on working columns

### Use Cases

- When you want to display only working columns on boards with many status columns
- When frequently switching between overview and detailed work

### Usage

- **Column Collapse/Expand**
  - Click status column headers to collapse/expand
  - Collapsed columns are shown as thin columns and can be expanded by clicking

- **Keyboard Shortcuts**
  - `Ctrl+Shift+E` (macOS: `Cmd+Shift+E`): Expand all columns
  - `Ctrl+Shift+C` (macOS: `Cmd+Shift+C`): Collapse all columns

- **State Persistence**
  - States are preserved after page reload
  - States are remembered per project and board


---

## Shortcut Key Display Feature

### Overview

Backlog standard shortcut keys are visually displayed to improve keyboard operation efficiency

### Use Cases

- When you want to learn Backlog's keyboard shortcuts
- When you want to reduce mouse operations and improve work efficiency

### Usage

- **Display**
  - Add shortcut key display to navigation items in Backlog
  - Display corresponding keys for each sidebar item

- **Tooltips**
  - Key descriptions available via tooltips when hovering over shortcut keys

---

## Issue Pending Feature

### Overview

Temporarily hold issues on the board for priority management

### Use Cases

- When you want to temporarily hold issues waiting for review or prioritize other tasks
- When you want to visually manage priorities on the board

### Usage

- **Toggle Pending State**
  - Click issue cards to toggle Pending state
  - Visually identified by card background color and icon

- **Visual Distinction**
  - Pending issues are displayed with dedicated colors and icons
  - Easily identify pending issues at a glance

- **Auto-Clear**
  - Pending state is automatically cleared when an issue is moved to a completed status (e.g., "Done", "Closed") (default: enabled)
  - You can disable this behavior in the extension settings (Extension Options or Popup) under "Issue Pending Feature" > "Auto-clear on completion"
  - Pending state can also be manually cleared by clicking the issue card again

---

## PR Format Auto-Insert Feature

### Overview

Automatically insert project-specific templates when creating pull requests

### Use Cases

- When you want to use unified pull request formats across the team
- When you want to save the effort of manually entering the same format every time

### Usage

- **Template Management**
  - Edit and manage project-specific templates in settings screen
  - Save by linking project keys with template content

- **Auto-Insert**
  - Automatically insert project-specific templates on pull request creation pages
  - Templates corresponding to the current project are automatically applied

---

## Issue Comment URL Copy Feature

### Overview

Add URL copy buttons to each comment on issues and pull requests, allowing you to copy direct links to comments with one click

### Use Cases

- When you want to share specific comments with other members
- When you want to make it easier to reference discussions within issues or pull requests

### Usage

- **Copy Button**
  - Copy buttons appear on each comment in issue detail and pull request pages
  - Click the button to copy the direct link URL to the clipboard

- **Supported Pages**
  - Issue detail pages
  - Pull request pages
  - In-screen issue display
