# OPEN-food-facts-estore_extension.
Sell stuff and see what sticks

# Project Summary: Open Food Facts Canada Online Store Extension
.The Problem
Canadian shoppers lack health transparency on major retail sites (Walmart, Loblaws, etc.) because Product UPCs are often missing or hidden. This gap prevents 1:1 matching with the Open Food Facts database.
The Solution
I will build a modular WXT-based browser extension that uses a Multi-Tiered Matching Logic to bypass the missing UPC blocker. This ensures users get Nutri-Score and Eco-Score data even when a barcode isn't explicitly listed.
Key Innovations
Fallback Matching: Uses Metadata Scraping (ld+json) → Weighted Fuzzy Search (Brand + Name + Weight) → User-Assisted Contributions.
DuckDB Integration: Transitioning from API-based calls to the Canadian DuckDB instance for high-performance, local analytical queries.
Bilingual Support: Dynamic rendering in English and French via the Knowledge Panels API.
Impact
This project turns the extension into a growth tool for the Open Food Facts Canada database while providing immediate value to consumers.
