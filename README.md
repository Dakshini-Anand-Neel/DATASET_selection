# 📑 Automated Dataset Preparation Framework: README

## Overview
This framework is a modular, cloud-native pipeline designed to streamline the discovery and acquisition of datasets across 15 high-impact domains (F01–A10). It eliminates the need for manual file handling by automating search, direct in-memory loading, and CSV conversion.

## 🚀 Key Features
- **Hierarchical Domain Selection**: Choose from predefined categories including Public Service, Education, Fintech, Cybersecurity, and more.
- **Multi-Source Discovery**: Aggregates real-time search results from **Hugging Face**, **OpenML**, **Kaggle**, **UCI ML Repository**, and **GitHub**.
- **Direct In-Memory Import**: Automatically loads datasets into a global Python variable `df` using APIs or URL streaming, bypassing the need for local downloads.
- **Auto-Snippet Generation**: Provides ready-to-use code snippets for common libraries (`datasets`, `openml`, `pandas`).
- **CSV Export**: Automatically prepares a downloadable CSV version of any acquired dataset.

## 🛠️ Usage Flow
1. **Select Project**: Use the dropdown menus in Section 2 to specify your domain and sub-project.
2. **Discover**: Run Section 3 to search global repositories for relevant data.
3. **Acquire**: Enter the **Dataset ID** from the search results into Section 4 and click **'Get Data & Code'**.
4. **Develop**: The data is now available in the `df` variable. You can also copy the provided code snippet to a new cell to make your import persistent.

## 📦 Dependencies
- `pandas`, `numpy`: Data manipulation.
- `datasets`: Hugging Face API integration.
- `openml`: OpenML dataset access.
- `ipywidgets`: Interactive UI components.

---
