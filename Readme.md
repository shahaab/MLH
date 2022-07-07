# Search for users and Display their Details
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
    <li><a href="#api-docs">API DOCS</a></li>
    <li><a href="#initial-setup">Initial Setup</a></li>
    <li><a href="#render-results">Render Results</a></li>
  </ol>
</details>

## About The Project

![MLH](https://user-images.githubusercontent.com/41134301/177699801-2444b4b4-2c2e-43b5-a0de-b242794d530b.png)
This project helps in fetching the data of the users using the Github API and displaying them.

### Built With

* ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
* ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
* ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

<!-- GETTING STARTED -->
## Getting Started
This website is build using HTML, CSS and Javascript. No other libraries are required or suggested.
To get a local copy up and running follow these simple steps.

### Prerequisites

* Code editor such as VScode.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/shahaab/MLH.git
   ```
2. Enter your name in `script.js`
   ```js
   getUser("ENTER YOUR NAME");
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

#### API DOCS

- [Github apis to get user details](https://api.github.com/users/)
- [Github apis to get user's repository details](https://api.github.com/users/repos)

- Ready to go url's

#### Initial Setup

- select form, input, results
- listen for submit events
- If empty value, display default
- create getUser()
- pass valid input value into the createUserCard()


#### Render Results

- iterate over the data fetched by API
- pull out name, bio, followers, following, no. of repos
- setup a card and put the above data into div with id 'user-info'
- pull out repo details such as name, url based on their stars
- put the repo details based on lexicographical order into div with id 'repos'  
- set the result and display it
