# Visibility Product for WooCommerce

**Visibility Product** is a powerful and lightweight WooCommerce plugin that gives you granular control over product visibility and purchase access.

Easily hide products, categories, or specific attributes from unwanted visitors, or create exclusive "VIP" areas, private stores, and targeted upsells without writing a single line of code.

## 🚀 Key Features

### 🎯 Flexible Targeting
Target exactly what you want to restrict:
*   **All Products** (Global rules)
*   **Specific Products** (Select by Name/ID)
*   **Categories**
*   **Tags**
*   **Product Attributes** (e.g., Color: Blue, Size: Large)

### 🛡️ Powerful Visibility Actions
Decide what happens when a user **doesn't** match your rules:
*   **Hide Completely:** The product disappears from the Shop, Category pages, Search results, and Related Products.
*   **Restrict Access:** The product remains visible, but the "Add to Cart" button is removed. You can:
    *   Redirect to a custom URL (e.g., Login/Register page).
    *   Show a custom error message.

### 🧠 Advanced Conditions Logic
Combine multiple conditions to create complex rules. Supports **AND** logic within rules.

*   **User Role:** Limit to VIPs, Wholesalers, Administrators, or Guests.
*   **Geo Location:** Restrict by Country or State/Province (e.g., "California Residents Only").
*   **Cart Value:** innovative upsells (e.g., "Spend $500 to see this exclusive gift").
*   **Cart Contents:** Cross-sell logic (e.g., "Show Lens Kit only if Camera is in cart").
*   **Purchase History:** Loyalty rewards (e.g., "Only for customers who bought X before").
*   **Stock Status:** Reserve low-stock items for loyal customers.
*   **Date & Time:** Schedule product launches or limited-time visibility.
*   **User ID / Login Status:** Target specific influencers or logged-in users.

### ⚙️ Global Protection Settings
*   **Search Engine Visibility:** Option to allow Google/Bing bots to crawl hidden products (good for SEO) while keeping them hidden from normal users.
*   **Global Redirects:** Set a default fallback URL for restricted content.
*   **Menu & Widget Support:** Automatically filters WooCommerce product widgets.

## 📦 Installation

1.  Download the `yeevisibility.zip` file.
2.  Go to your WordPress Admin Dashboard.
3.  Navigate to **Plugins > Add New**.
4.  Click **Upload Plugin** and select the zip file.
5.  Click **Install Now** and then **Activate**.

## 🔧 Configuration

All settings are located under **WooCommerce > Settings > Product Visibility**.

### 1. The "Rules" Tab
Here you define your visibility logic.
1.  Click **Add Rule**.
2.  **Filter Type:** Choose what to hide (e.g., Category: Premium).
3.  **Visibility Action:** Choose "Show" (Whitelist) or "Hide" (Blacklist).
    *   *Tip: "Show" is usually easier. E.g., "Show Premium Category to VIPs" automatically hides it from everyone else.*
4.  **Conditions:** Add your logic (e.g., Role IS VIP).

### 2. The "Settings" Tab
Configure global behavior.
*   **Hide from Search:** Check this to remove restricted products from standard WordPress search results.
*   **Redirect URL:** Where should unauthorized users go? (Default: Shop Page).

## 📖 Documentation
Detailed HTML documentation with examples is included in the plugin:
*   [Main Documentation](docs/index.html)
*   [Example: VIP Exclusive Products](docs/example-vip-perfume.html)
*   [Example: Geo Location Restrictions](docs/example-geo-location.html)
*   [Example: Cross-Sell by Cart Content](docs/example-cart-contains.html)

## 💻 Requirements
*   WordPress 5.0+
*   WooCommerce 4.0+
*   PHP 7.4+

## 📄 License
GPLv2 or later.
