Project Overview:

MarketHub is a comprehensive web-based marketplace application built using the Flask framework. This application enables users to register, log in, and manage items within a marketplace. The app leverages SQLite for data storage, Jinja2 for templating, and Flask-WTF for handling forms.

Technologies Used

	    •	Flask Framework: Provides the core web framework functionalities.
	    •	SQLite: A lightweight, disk-based database used for storing application data.
	    •	Jinja2: A templating engine for rendering HTML.
	    •	Flask-WTF: Integrates Flask with WTForms for form handling.
	    •	SQLAlchemy: An ORM (Object-Relational Mapping) library for database interactions.

Real-Life Implementation

This application can be used in various real-life scenarios, such as:

	    •	Online Marketplaces: Facilitates the creation of an online marketplace where users can buy and sell items.
	    •	Inventory Management: Helps small businesses manage their inventory and sales.
	    •	User Management: Enables secure user registration and authentication for web applications.

To access container after building:
	docker run -p 5000:5000 --name flaskapp --rm -d mohamedaklamaash/flaskapp:latest

To run a docker container in aws:
	-> create an ec2 instance (allow all traffic)
	-> sudo yum update -y
	-> sudo dnf install docker
	-> sudo systemctl start docker
	-> sudo systemctl enable docker
	start the container and expose the port 80 and app's port needs to be 5000