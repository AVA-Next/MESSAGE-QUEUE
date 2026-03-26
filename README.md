# Message Queue Notification Widget

A robust Zoho CRM Notification Widget designed for efficient record tracking and management.

## Project Overview

This widget provides a streamlined interface for viewing and managing "Open" records within Zoho CRM. It uses a "clear-and-render" logic to ensure that only the most relevant and up-to-date information is displayed to the user.

## Features

- **Robust Search and Filter**: Automatically identifies and displays "Open" records.
- **Clear-and-Render Logic**: Ensures a clean state before each render to prevent duplicate or stale data.
- **Manual Refresh**: Allows users to manually fetch the latest records from the server.
- **Enterprise UI**: Clean, professional design optimized for the Zoho CRM environment.

## Getting Started

### Prerequisites

- [Zoho Extension Toolkit (ZET)](https://www.zoho.com/crm/developer/docs/extensions/zet-cli.html) installed globally.

### Packing the Extension

To pack the extension for deployment:

1. Navigate to the `Notification_Widget` directory:
   ```bash
   cd Notification_Widget
   ```
2. Run the pack command:
   ```bash
   zet pack
   ```
The packed extension will be available in the `dist` folder.

## Development

The core logic and structure of the widget are located in:
- `Notification_Widget/app/widget.html`: Main UI and logic.