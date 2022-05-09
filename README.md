<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/javiermendez-coder/express_api">
    <img src="https://raw.githubusercontent.com/othneildrew/Best-README-Template/master/images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Express API</h3>

  <p align="center">
    Project to set up a express API server
    <br />
    <a href="https://github.com/javiermendez-coder/express_api"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/javiermendez-coder/express_api/issues">Report Bug</a>
    ·
    <a href="https://github.com/javiermendez-coder/express_api/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Practice project designed by [Carlo Gilmar][carlogilmar] focused on teaching how to create common API endpoints (such as: GET, POST, PUT, and DELETE) with the express module, and access them through Postman.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [JavaScript](https://www.javascript.com/)
* [express](https://expressjs.com/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/javiermendez-coder/express_api.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE -->
## Usage

This API allows you to access to a made up "explorers" (basically the way the instructors refer to us) list from Launch X. You can access it via browser or API platforms like [Postman][postman].

### HTTP Requests examples

* Obtain the explorers list
  ```
  GET localhost:3000/v1/explorers
  ```
* Obtain an explorer by ID
  ```
  GET localhost:3000/v1/explorers/:id
  ```
* Create an explorer 
  ```
  POST localhost:3000/v1/explorers/
  
  body content: { "name": "bar" }
  ```
* Update an explorer by ID
  ```
  PUT localhost:3000/v1/explorers/:id

  body content: { "id": 0 }
  ```
* Delete an explorer by ID
  ```
  DEL localhost:3000/v1/explorers/:id
  ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Javier Méndez - javiermendez0299@gmail.com.com

Project Link: [https://github.com/javiermendez-coder/express_api](https://github.com/javiermendez-coder/express_basic)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Carlo Gilmar][carlogilmar]
* [Launch X][launchx]

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/javiermendez-coder/express_api.svg?style=for-the-badge
[contributors-url]: https://github.com/javiermendez-coder/express_api/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/javiermendez-coder/express_api.svg?style=for-the-badge
[forks-url]: https://github.com/javiermendez-coder/express_api/network/members
[stars-shield]: https://img.shields.io/github/stars/javiermendez-coder/express_api.svg?style=for-the-badge
[stars-url]: https://github.com/javiermendez-coder/express_api/stargazers
[issues-shield]: https://img.shields.io/github/issues/javiermendez-coder/express_api.svg?style=for-the-badge
[issues-url]: https://github.com/javiermendez-coder/express_api/issues
[carlogilmar]: https://github.com/carlogilmar/
[launchx]: https://github.com/LaunchX-InnovaccionVirtual
[postman]: https://www.postman.com/
