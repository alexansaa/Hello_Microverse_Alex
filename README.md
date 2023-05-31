# Hello_Microverse_Alex
Test Microverse repository is implementing awesome features! Writen by Alexander Saavedra

<a name="readme-top"></a>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ (OPTIONAL)](#faq)
- [📝 License](#license)

# 📖 [Hello_Microverse_Alex] <a name="about-project"></a>

> This project meant to be a sample test for implementing different technologies for control and quality of code.

**[Hello_Microverse_Alex]** This project is the first professional repository that I have implemented. Microverse has taught me to use different technologies for improving code quality and show more professionalism when developing in real-life situations.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

> This repository uses HTML and CSS. For code quality I am using Lighthouse, Webhint and Stylelint. Required configuration files are providen by Microverse.

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML">HTML</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS">CSS</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li>N/A</li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li>N/A</li>
  </ul>
</details>

### Key Features <a name="key-features"></a>

> This repository has 3 important features relevant for the Micronaut path:

- **[Custom_Readme_File]**
- **[HTML_&_CSS_Linters]**
- **[GitHub_Repository]**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🚀 Live Demo <a name="live-demo"></a>

- [Demo link is coming soon](#)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need three basic technologies:
- Web Browser (any like Safari, Chrome or Edge)
- Text Editor (Visual Studio Code prefered to follow this guide)
- NodeJS Long Term Support installation in your local machine

### Setup

Clone this repository to your desired folder:

```
  cd my-local-folder
  git clone https://github.com/alexansaa/Hello_Microverse_Alex.git
```

### Install

Install this project following the next steps:

- Set-up GutHub Actions: In the first commit of your feature branch create a .github/workflows folder and add a copy of ".gothub/workflows/linters.yml" to that folder (don't make any changes to that file)
- Set-up linters in your local env: the npm package manager is going to create a "node_modules" directory to install all of your dependencies. You shouldn't commit that directory. To avoid that, you can create a ".gitignore" file and add "node_modules/" to it.
    - Lighthouse:
        - Download Chrome
        - Instal the Long-Term Support version of Node
        - Install Lighthouse with...

```
  npm install -g lighthouse
```

    - Webhint: Copy ".hintrc" to the root directory of your project (Don't make any changes in this file). Then use next commands

```
  npm init -y
  npm install --save-dev hint@7.x
  npx hint .
```
    - Stylelint: Copy ".stylelintrc.json" to the root directory of your project (Don't make any change to the file)

```
  npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
  npx stylelint "**/*.{css,scss}"
```
After you have successfully install all this packages, run the Linter test in the GitHub for desktop app and fix any Linter errors.

### Usage

To run the project, you should double click the index.html file. You could also press F5 in Visual Studio Code with your clone of this project open.

Running Linter errors need you to push your commit changes to GitHub so the desktop app can run check test.

### Run tests

There are not test provided so far.

### Deployment

You can deploy this project using:

Deploy this project on any websever

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Authors <a name="authors"></a>

👤 **Alexander Saavedra**

- GitHub: [@alexansaa](https://github.com/alexansaa)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Future Features <a name="future-features"></a>

- [ ] **New Logo**
- [ ] **Animated Welcome**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

If you like this project give me a star.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank every who continues supporting me.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./MIT.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
