# 📂 File Backup & Search Tool

A Python CLI utility that helps you find files recursively, filter them by creation time, and securely copy or archive them.

> **Note:** The program interface (prompts) is currently in Russian, but this documentation explains usage in English.

## 🚀 Features

* **Recursive Search:** Scans directories to find files matching your query.
* **Time Filter:** Allows you to find files created/modified within the last N hours.
* **Smart Copying:** Preserves file metadata and automatically renames files if duplicates exist (e.g., `file(2).txt`).
* **Archiving:** Can compress found files into a timestamped ZIP archive.
