---
permalink: backup-your-mysql-database-with-phpmyadmin/
node_id: 661
title: Backup your MySQL database with phpMyAdmin
type: article
created_date: '2011-03-16'
created_by: Rackspace Support
last_modified_date: '2016-01-12'
last_modified_by: Stephanie Fillmon
product: Cloud Sites
product_url: cloud-sites
---

### Backing Up Your MySQL Database

1. Log in to the [online manager (phpMyAdmin)](/how-to/rackspace-cloud-sites-essentials-phpmyadmin-database-management-interface).

2. To view information, click on a database or table in the left frame
   as shown in the following figure:

   <img src="{% asset_path cloud-sites/backup-your-mysql-database-with-phpmyadmin/phpmyadmin-dbs.png %}" alt="" />

3. To export the database to a backup file, click **Export**:

   <img src="{% asset_path cloud-sites/backup-your-mysql-database-with-phpmyadmin/phpmyadmin-export.png %}" alt="phpMyAdmin Export tab" />

4. To save the backup file to your system, click **Save as
   file**.

   When you save the file, you can change the name of the backup file and the
   compression method, or use the defaults. Compression reduces the size of the backup file.
   The recommended compression method is *gzipped*:

   <img src="{% asset_path cloud-sites/backup-your-mysql-database-with-phpmyadmin/phpmyadmin-saveasfile.png %}" alt="" />

5. To start the backup process, click **Go**.

6. When the backup process completes, follow the prompt to save the file to your desktop.


### Finish Line

You have just created a backup of your MySQL database. If you have any issues, questions or concerns,
contact our technical support 24x7 via phone, chat, or by submitting a ticket through your control panel.
