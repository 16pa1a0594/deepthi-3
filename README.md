# project-3
packages: Python3 Vagrant VirtualBox psycopg2

Setup Project:

Install Vagrant and VirtualBox
Download or Clone fullstack-nanodegree-vm repository.
Download the data from here.
Unzip this file after downloading it. The file inside is called newsdata.sql.
Copy the newsdata.sql file and content of this current repository, by either downloading or cloning it from Here
Launching the Virtual Machine:

Launch the Vagrant VM inside Vagrant sub-directory in the downloaded fullstack-nanodegree-vm repository using command:
$ vagrant up

Then Log into this using command:
$ vagrant ssh

Change directory to /vagrant and look around with ls.
Setting up the database and Creating Views:

Load the data in local database using the command:
psql -d news -f newsdata.sql

The database includes three tables:

The authors table includes information about the authors of articles.
The articles table includes the articles themselves.
The log table includes one entry for each time a user has accessed the site.

Use \c news to connect to database.
running python file: python3 log.py
# deepthi-3# deepthi-3
