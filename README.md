# Odoo_Book_store
BOOKSTORE MODULE - ODOO 17
==========================

📦 MODULE NAME: book_store  
🛠️ Version: 1.0  
📚 Description: A fully functional bookstore management system for Odoo 17.

-----------------------------------------------------
✅ FEATURES
-----------------------------------------------------
- Book management (title, author, publisher, ISBN, price, stock, genres, cover image)
- Book age auto-computation
- Archive books manually or automatically (scheduler)
- Wizard to add authors quickly from book form
- Genre assignment (many-to-many)
- Chatter integration (track changes in stock, price, publish date, etc.)
- Activities & automated notifications (e.g., reorder reminders)
- Reporting menu: Book Summary with filters
- Kanban view with cover image & age color-coded badges
- Unit tests included (book age, archiving, wizard)
- Demo data for quick testing

-----------------------------------------------------
🧩 DEPENDENCIES
-----------------------------------------------------
- Python 3.10+
- Odoo 17.0
- PostgreSQL (configured and running)
- Wkhtmltopdf (for PDF report support)

-----------------------------------------------------
🚀 INSTALLATION
-----------------------------------------------------
1. Clone or copy the module into your Odoo addons directory:
   `odoo/addons/book_store`
2. Ensure your `odoo.conf` file includes the correct addons path
3. Restart the Odoo server:
  `python odoo/odoo-bin -c odoo.conf`
4. Upgrade the module:
   `python odoo/odoo-bin -c odoo.conf -u book_store`
5. Login to Odoo UI at:
    http://localhost:8069
   
-----------------------------------------------------
🧭 USAGE
-----------------------------------------------------
▶ Book Management:

Menu: Book Store → Books → Manage Books

Views: Kanban, Tree, Form

▶ Add New Book:

Click “Create”

Fill in details (name, author, genre, price, etc.)

Use "Add New Author" button if author doesn’t exist

▶ Auto Archive:

Books older than a set threshold are auto-archived (via scheduled action)

▶ Reporting:

Menu: Book Store → Reports → Book Summary

Filter books by genre, stock, and age

▶ Chatter & Tracking:

On each book, track changes to price, stock, etc.

Notifications appear in form chatter (bottom of form)

▶ Activities:

If stock is below 5 → activity is created

If book is archived → manager is notified

-----------------------------------------------------
📞 SUPPORT
-----------------------------------------------------
Telegram: https://t.me/Justkaltsegaye

