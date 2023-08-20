# GitHub Web Scraping Project

This project involves scraping information from GitHub's topics, retrieving repositories within those topics, and creating separate CSV files for each topic with relevant data.

## Project Overview

The project aims to automate the process of collecting repository information from GitHub topics. The main steps of the project are:

1. Scraping the [GitHub Topics page](https://github.com/topics) to get a list of topics.
2. For each topic, gathering topic title, URL, and description.
3. For each topic, collecting the top 25 repositories from the topic page.
4. Extracting repository name, URL, username, and star count for each repository.
5. Generating separate CSV files for each topic with repository information.

## Getting Started

To use this project:

1. Clone the repository to your local machine.
2. Install the required libraries listed in the `requirements.txt` file using `pip install -r requirements.txt`.
3. Run the Python script to scrape GitHub topics and repositories.

## Usage

1. Run the script `scrape_github_topics.py` to initiate the scraping process.
2. The script will create a CSV file for each topic in the `output` directory.
3. Each CSV file will contain repository information with columns: "Repo Name", "Username", "Stars", "Repo URL".

## Dependencies

- [Python](https://www.python.org/) - The programming language used for the project.
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) - Python library for web scraping.
- [Requests](https://docs.python-requests.org/en/latest/) - Python library for making HTTP requests.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, feel free to open an issue or a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Special thanks to the contributors and libraries that made this project possible.

