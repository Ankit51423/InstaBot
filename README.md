# InstaBot
# Problem statement
Your friend has opened a new Food Blogging handle on Instagram and wants to get famous. He wants to follow a lot of people so that he can get noticed quickly but it is a tedious task so he asks you to help him. As you have just learned automation using Selenium, you decided to help him by creating an Instagram Bot.

You need to create different functions for each task.

# Note :
Don’t forget to remove your Username and Password from the python notebook before submission.

Replace your username and password by ‘SAMPLE USERNAME’ and ‘SAMPLE PASSWORD’ where you have used them in your code for logging in to instagram

Upload your code file for submission of this project

Sure, here's a comprehensive README for your InstaBot project, covering all essential aspects:

---

# Start

InstaBot is a Python-based automation project using Selenium to interact with Instagram. It can log in to an Instagram account, search for specific keywords, and perform various actions on the search results.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Features](#features)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

InstaBot automates the process of logging into Instagram, searching for keywords, and interacting with search results. This can be useful for marketing, data collection, or simply automating repetitive tasks on Instagram.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/instabot.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd instabot
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Install Chrome WebDriver:**

    Download Chrome WebDriver from [here](https://sites.google.com/a/chromium.org/chromedriver/) and ensure it is in your system's PATH.

## Project Structure

```
instabot/
│
├── notebooks/
│   └── InstaBot part 1.ipynb   # Jupyter notebook with the bot implementation
│
├── requirements.txt            # Required libraries
├── README.md                   # Project documentation
└── LICENSE                     # License file
```

## Usage

1. **Open the Jupyter notebook:**

    ```bash
    jupyter notebook notebooks/InstaBot part 1.ipynb
    ```

2. **Follow the steps in the notebook:**

    - **Login:** Logs into Instagram with provided credentials.
    - **Search:** Searches for a specified keyword (e.g., "food") and prints the names of the Instagram handles that appear in the search results.

## Features

- **Login Automation:** Automatically logs into Instagram using provided credentials.
- **Search Automation:** Searches for a specified keyword and lists Instagram handles from the search results.
- **Notification Suppression:** Suppresses "Turn On Notifications" prompt.

## Configuration

To configure InstaBot, modify the relevant cells in the Jupyter notebook:

1. **Login Credentials:**

    ```python
    username_box.send_keys('your_username')
    password_box.send_keys('your_password')
    ```

2. **Search Keyword:**

    ```python
    search_keyword = 'food'
    ```

## Dependencies

- **Selenium:** Web automation library.
- **BeautifulSoup:** Library for web scraping.
- **Chrome WebDriver:** Driver for Chrome browser automation.

Install the required Python packages using:

```bash
pip install -r requirements.txt
```

Ensure Chrome WebDriver is installed and in your system's PATH.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

Please read the [contributing guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to adjust the README to better fit any additional features or details specific to your project. If you have more specific information you'd like included, let me know!
