# code95Theme
📄 Installation Guide for Nafez Tech WordPress Theme
🚀 Step 1: Install the Theme (Nafez Tech)
Upload the nafez-tech theme to this directory:
/wp-content/themes/nafez-tech/

Go to WordPress Dashboard → Appearance > Themes

Activate the Nafez Tech Theme.

🚀 Step 2: Install Required Plugins (Auto Added via MU-Plugins)
1️⃣ After you extract the project files, you will find a folder:


/mu-plugins/
2️⃣ Upload the folder to this path in your WordPress installation:

/wp-content/mu-plugins/

Note: This plugin handles:
-Featured Posts
-Sticky Posts (Main Section)
-Post Selection from Dashboard

No need to activate anything manually.
Any plugin inside the mu-plugins folder runs automatically.

🚀 Step 3: Install & Activate Elementor
Go to WordPress Dashboard → Plugins > Add New

Install and activate Elementor (Pro if needed).

🚀 Step 4: Import Elementor Templates (Full Site Kit)
Go to:
Elementor → Tools → Import / Export Kit

Select the provided file:
/elementor-kit/export-kit.zip

Import everything:

Templates

Header / Footer

Pages / Posts (Optional)

Global Colors / Fonts

Site Settings

🚀 Step 5: Import the Database (Optional for Demo Content)
Go to phpMyAdmin or hosting database panel.

Select your database.

Import:
/database/nafez-tech-database.sql

This includes:

Menus

Categories

Sticky / Featured Posts

Views for Top 5 Stories

Posts assigned to correct sections.

🚀 Step 6: Upload Media (Optional if needed)
Upload /uploads/ contents to:
/wp-content/uploads/

your-project/
├── nafez-tech/           (Theme Folder)
├── mu-plugins/           (Custom Plugin for Featured Posts)
├── elementor-kit/        (Elementor Full Site Export)
├── database/             (SQL Dump)
├── uploads/              (Optional Media)
