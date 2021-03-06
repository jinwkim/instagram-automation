<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/jinwkim/instagram-automation">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Instagram Automation</h3>

  <p align="center">
    Using Python and Selenium to automate the process of increasing Instagram engagement -- automatically navigate to top hash tags, click on top recent images, like and comment, and follow the user.
    <br />
    <a href="https://github.com/jinwkim/instagram-automation"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/jinwkim/instagram-automation">View Demo</a>
    ·
    <a href="https://github.com/jinwkim/instagram-automation/issues">Report Bug</a>
    ·
    <a href="https://github.com/jinwkim/instagram-automation/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

If you are actively trying to get new followers for your Instagram profile, you may spend hours looking through new content, leaving likes and comments, and following new users. This project aims to alleviate some of the burden by automating the process. The Python code in this project will automatically open up a browser, log in with your account into Instagram, navigate to hash tags you specify, click on the first "x" number of top images, leave a like/comment (you can alter the pool of randomly selected comments), and follow the user.


### Built With

* [Python](https://www.python.org/downloads/) - coding language used
* [Jupyter](https://jupyter.org/) - used to run Python code
* [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/home/) - used to automate navigating the web



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* Python
* [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/home/) / Selenium
* [Jupyter Notebook](https://jupyter.org/)

### Installation
 
1. Clone the repo
```sh
git clone https://github.com/jinwkim/instagram-automation.git
```
2. Install [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/home/) from the web and save in an accessible directory.

3. Start Jupyter Notebook and open the instagram-automation.ipynb file.
```sh
jupyter notebook
```
4. In the instagram-automation.ipynb notebook, edit the following lines:
```python
chromedriver_path = "/Users/jinwkim/Downloads/chromedriver" # Change to your chromedriver path
un, pw = "", "" # Change to your username/password
hashtag_list = ["Food","FoodPorn","InstaFood"] # Change to your desired hashtags
```


<!-- USAGE EXAMPLES -->
## Usage

Use a Jupyter Notebook to run the code!



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/jinwkim/instagram-automation/issues) for a list of proposed features (and known issues).


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

[Jin Kim](https://itsjinkim.com/) - [@jinwoookim_](https://www.instagram.com/jinwoookim_/) - jinwkim@alum.mit.edu

Project Link: [https://github.com/jinwkim/instagram-automation](https://github.com/jinwkim/instagram-automation)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Fábio Neves](https://towardsdatascience.com/increase-your-instagram-followers-with-a-simple-python-bot-fde048dce20d) - Inspiration for Code
* [othneildrew](https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md#about-the-project) - README Template



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/jinwkim/instagram-automation.svg?style=flat-square
[contributors-url]: https://github.com/jiwnkim/instagram-automation/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jinwkim/instagram-automation.svg?style=flat-square
[forks-url]: https://github.com/jinwkim/instagram-automation/network/members
[stars-shield]: https://img.shields.io/github/stars/jinwkim/instagram-automation.svg?style=flat-square
[stars-url]: https://github.com/jinwkim/instagram-automation/stargazers
[issues-shield]: https://img.shields.io/github/issues/jinwkim/instagram-automation.svg?style=flat-square
[issues-url]: https://github.com/jinwkim/instagram-automation/issues
[license-shield]: https://img.shields.io/github/license/jinwkim/instagram-automation.svg?style=flat-square
[license-url]: https://github.com/jinwkim/instagram-automation/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/jinwoookim/
[product-screenshot]: images/screenshot.png
