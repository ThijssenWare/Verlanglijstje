# Wishlist App Requirements

## 📖 Overview
A static **wishlist** hosted on **GitHub Pages**, where:
- Friends & family can **view the wishlist**.
- You can **manually add items** by editing the code.
- Visitors can **mark items as bought** via **GitHub Issues**.
- GitHub Actions **automatically updates** the wishlist every hour.

## ✅ Features
### 1. **Static Web Page**
- Hosted on GitHub Pages.
- Displays the **wishlist items** dynamically.

### 2. **GitHub Issues for User Interaction**
- Visitors mark items as "Bought" using **GitHub Issues**.
- Issues include the **item name** and **buyer’s name**.

### 3. **GitHub Actions for Automated Updates**
- Reads **wishlist issues** submitted by visitors.
- Updates `wishlist.json` dynamically using **GitHub API**.

### 4. **Wishlist items**
- Each item has a name, url and potentially an image (stored statically in this repo)
- The wishlist items are stored in a .json file.

## 🏗️ Tech Stack
- **GitHub Pages** → Hosts the site.
- **HTML / CSS / JavaScript** → Frontend for interaction.
- **GitHub API** → Fetches submitted issues.
- **GitHub Actions** → Automates updates.

### **UI**
- App needs to have a modern look and feel like it is made by professional website builders.

