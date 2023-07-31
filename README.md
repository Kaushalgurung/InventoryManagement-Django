# InventoryManagement-Django
Inventory Management System-Django and SQLite
IMS is a simple inventory management software created for the requirements of a company.
The software is capable of keeping track of incoming and outgoing stock with a dynamically rendered bill.
Each supplier is provided with a profile where they can see the history of their transactions with the company.
#Features
1. Interactive Chart to display current available stock
2. Stock details like current available stock are maintained
3. Incoming transactions are done through purchases
4. Outgoing transactions are done through sales
5. Every transaction performed through the software is recorded
6. Bill is dynamically rendered and can be printed
7.Separate profiles are maintained for suppliers

#**Instructions**
- Install the Requirements: pip install -r requirements.txt
- Then, make database migrations: python manage.py makemigrations
- python manage.py migrate
- And finally, run the application: python manage.py runserver

For Admin Account, please create one with superuser!
