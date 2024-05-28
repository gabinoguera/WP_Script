WP-Script
Overview
WP-Script is a Python-based solution designed to automate the creation of WordPress posts from a dataset of universities. This script reads data from Excel files, processes and cleans it, and then uses the WordPress API to create posts and assign appropriate tags. This automation is ideal for managing large volumes of content efficiently and accurately.
This Repo is a complement to the article: https://ghendigital.com/code/el-trabajo-de-una-semana-en-una-manana-con-la-api-de-wordpress-y-python/

Use Case
In this project, we aimed to create a comprehensive directory of Mexican universities. Given the large amount of data and the need for consistent classification and tagging, we automated the process using Python and the WordPress API. This approach saved significant time, ensured data accuracy, and allowed for easy scalability.

Repository Structure
DFbuilder.py: Contains the logic for reading, cleaning, and structuring the data from multiple Excel sheets into a unified DataFrame.
autopost.py: Handles the interaction with the WordPress API, creating posts and assigning tags based on the processed data.

Getting Started
Prerequisites
Python 3.x
pandas library
requests library
Install the required libraries using pip:

sh
Copiar código
pip install pandas requests

Setup
Clone the repository:

sh
Copiar código
git clone https://github.com/yourusername/WP-Script.git

Navigate to the project directory:
sh

Copiar código
cd WP-Script

Usage
Data Processing:

Ensure your Excel file with data is ready, you can use GPT for the necessary logic.
Run the DFbuilder.py script to read and clean the data:

sh
Copiar código
python DFbuilder.py
This will generate a cleaned and structured DataFrame.

WordPress API Interaction:

Configure your WordPress API credentials in autopost.py.
Run the autopost.py script to create posts and tags in WordPress:

sh
Copiar código
python autopost.py

Example
Assuming you have an Excel file named universidades.xlsx, the process will:

Read and clean the data from the Excel file.
Create posts for each university in WordPress.
Assign appropriate tags (e.g., district, public/private, online) to each post.
Benefits

Efficiency: Automates the creation of WordPress posts, saving significant time and effort.
Accuracy: Ensures consistent and error-free data entry.
Scalability: Easily handles large datasets and can be re-run for updates.
Maintainability: Simplifies content management by programmatically handling posts and tags.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

Feel free to adjust the repository URL, your GitHub username, or any other details as necessary.
