Slab Inventory Project

Project Overview
The Slab Inventory Project is a web-based application designed to help users explore and compare various types of slab materials—such as granite, marble, and other natural stones—used primarily in construction and decoration. The application provides a user-friendly interface for uploading images of desired slab materials and retrieving the closest matches from an extensive slab database.

Features

•	Image Upload: Users can upload images of slab materials they are interested in.

•	Material Comparison: The application compares the uploaded images against a pre-existing database and finds the most similar slab materials using advanced image processing techniques.

•	Interactive UI: Offers a clean and interactive interface for users to easily navigate through different slab options.

•	Database Search: Users can perform searches based on slab characteristics such as color, texture, and material type.
Technologies Used

•	Python: Backend logic including image processing and database interaction.

•	Flask: Serves the backend application and handles HTTP requests.

•	MySQL/MariaDB: Manages and stores slab data and user queries.

•	HTML/CSS/JavaScript: Frontend presentation and interaction layers.

•	Phusion Passenger: Application server for managing and deploying the Flask application.

•	Google Cloud AI: Utilizes Google's machine learning technologies for image comparison and analysis.

Getting Started

Prerequisites
•	Python 3.8 or higher
•	Pip and virtualenv
•	MySQL/MariaDB server
•	Access to a web server with Phusion Passenger support (optional for deployment)

Installation

1.	Clone the repository:
git clone https://github.com/Slabcrafters/slabinventory.git
cd slab-inventory

2.	Set up a Python virtual environment and activate it:
 python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3.	Install the required Python packages:
pip install -r requirements.txt

4.	Configure your database settings in config.py or through environment variables:
DATABASE_URI = 'mysql://username:password@localhost/slabinventory' 

5.	Initialize the database (ensure your MySQL/MariaDB server is running):
python init_db.py 

6.	Run the application locally:
flask run 
This will start the server on http://localhost:5000.

Deploying to Production
Follow your web hosting provider's instructions to deploy the Flask application. Ensure environment variables are properly configured for production settings.

Usage
Navigate to the application URL, upload a slab image, and view similar slabs retrieved from the database. Use the search function to filter slabs by specific attributes.

Contributing
Contributions are welcome! Please fork the repository and submit pull requests, or create issues for any bugs you've noticed or features you would like to see implemented.

License
Distributed under the MIT License. See LICENSE for more information.

Contact
Your Name - cferrio@gmail.com
Project Link: https://github.com/slabcrafters/slabinventory

# slabinventory
