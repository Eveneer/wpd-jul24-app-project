# 🧪 Application Project – WordPress Developer @ Eveneer

Hello!

Thank you for your interest in applying for the **Senior WordPress Developer** position at **Eveneer**. As part of the hiring process, we request you complete a **practical project** that demonstrates your ability to work with Elementor, custom theme/plugin development, and frontend layout accuracy.

We estimate the total time required to complete the project is **8–12 hours**, depending on your familiarity with the tools.

---

## 🛠️ Tech Stack & Requirements

- WordPress (latest version)
- Elementor (free or pro, depending on your license)
- ACF (free or pro)
- Custom plugin development
- Theme can be custom or a starter theme (e.g., Hello Elementor, or your own blank theme)

---

## 📄 Task 1: Elementor Page Replication (No HTML widget allowed)

**Objective:** Replicate the following Figma designs using only existing Elementor widgets.

- [**📱 Mobile Design:**](https://www.figma.com/proto/hy9pL97ycIi1G5m0WvzW0Q/CH-Arch-Academy?page-id=152%3A1787&node-id=152-1788)

- [**💻 Desktop Design:**](https://www.figma.com/proto/hy9pL97ycIi1G5m0WvzW0Q/CH-Arch-Academy?page-id=104%3A174&node-id=141-273)

### Rules

- ❌ You **must not use** the **HTML widget**
- ✅ You **must only use** Elementor's **built-in widgets**
- ✔️ Design should be responsive (match both mobile and desktop layouts)
- 📐 Fonts, spacing, sizing, and alignment should be as accurate to the design as possible

---

## 🔌 Task 2: Create a Simple Custom Plugin

**Objective:** Create a WordPress plugin named `eveneer-cta-tracker` with the following functionality:

### Plugin Functionality

1. **Track CTA Clicks**
   - Use JavaScript to track clicks on buttons with the class `eveneer-cta`
   - Store the following in the database:
     - Page URL
     - Button text
     - Timestamp of click
     - IP address (use `wp_get_user_ip()` or `$_SERVER['REMOTE_ADDR']`)

2. **Admin UI**
   - Add a menu item in the admin sidebar: `Eveneer CTA Tracker`
   - Show a table listing:
     - Button text
     - Page URL
     - Number of clicks
     - Last clicked time

3. **Bonus (Optional but appreciated)**
   - Export functionality to CSV
   - Display a chart of clicks over time (e.g., using Google Charts or Chart.js)

---

## 📦 Submission Instructions

1. Create a **private GitHub repository** named `eveneer-wp-project`
2. Your project should include:
   - The Elementor-built page as a template or page export (`.json` file or database export if needed)
   - Your custom plugin inside `/wp-content/plugins/eveneer-cta-tracker`
   - A `README.md` with:
     - Setup instructions
     - Any assumptions or special notes
3. Add **`even-devs`** to the repository as a **collaborator**
4. Submit your **repository link** via the application form or email

---

## ✅ Evaluation Criteria

- Visual accuracy in Elementor (without custom HTML)
- WordPress coding best practices
- Clean and secure plugin development
- Admin UI usability
- Code readability and structure
- Bonus feature implementation (optional)

---

Good luck! We’re looking forward to seeing your work.
