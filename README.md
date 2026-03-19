# OPEN-food-facts-estore_extension.
Sell stuff and see what sticks

# Project Summary: Open Food Facts Canada Online Store Extension
 1. The Problem
Canadian shoppers lack health transparency on major retail sites (Walmart, Loblaws, etc.) because Product UPCs are often missing or hidden. This gap prevents 1:1 matching with the Open Food Facts database.
 2. The Solution
I will build a modular WXT-based browser extension that uses a Multi-Tiered Matching Logic to bypass the missing UPC blocker. This ensures users get Nutri-Score and Eco-Score data even when a barcode isn't explicitly listed.
 3. Key Innovations
## 🚀 Technical Progress: Proof of Concept (March 2026)

I have successfully implemented a functional prototype using the **WXT framework** that demonstrates the core "Multi-Tiered Matching" logic proposed for this project.

### Key Accomplishments:
- **Resilient Extraction:** Implemented a **JSON-LD Metadata Parser** to extract high-fidelity product names and brands directly from the site's structured data. This successfully bypasses "False Positives" caused by "Related Products" carousels on Walmart's SPA.
- **Smart Search Logic:** Integrated a sanitization layer that strips marketing "noise" (e.g., "Family Size", "Rollback", weights) to improve API matching accuracy.
- **Live API Integration:** Real-time fetching from the [Open Food Facts API](https://world.openfoodfacts.org/) to display Nutri-Scores directly on retail product pages.
- **Reactive UI:** Built a `MutationObserver` and polling-based UI that updates instantly as users navigate between products without requiring a page refresh.

### Demo:
*Current status: Successfully identifies products and fetches Nutri-Scores (e.g., Nutrela Soya Chunks → Nutri-Score B).*
