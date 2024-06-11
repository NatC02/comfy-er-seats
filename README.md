<div id="top"></div

![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white) ![Alpine.js](https://img.shields.io/badge/alpinejs-white.svg?style=for-the-badge&logo=alpinedotjs&logoColor=%238BC0D0)!
[PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Javascript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

![vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)

<br />
<div align="center">

![logo](./imgs/logo.png)

  <p align="center">
     Comfy-er Seats is an app built with the purpose to be language agnostic. The application is made with PHP's Laravel 10 framework, TailwindCSS, vite, and MySQL database.
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

Built and implemented with:

- laravel sanctum (lightweight authentication)
- guzzle (PHP HTTP client)
- flowbite (UI library)
- alpinejs (minimal overhead, using JS behavior directly in markup)
- & much more!

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

1. Clone the repo
   ```sh
   git clone https://github.com/NatC02/comfy-er-seats.git
   ```
2. cd into dir and install NPM packages and composer dependencies
   ```sh
   npm install
   composer install
   ```
3. Copy .env.example to .env
   ```sh
   cp .env.example .env
   ```
4. generate app key
   ```sh
   php artisan key:generate
   ```
5. run database migrations
   ```sh
   php artisan migrate
   ```
6. Start development apache server and vite 
   ```sh
   php artisan serve
   npm run dev
   ```

### Built with:

- Django
- Vue
- HTML5
- Tailwind

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Acknowledgments

Some of the resources I checked while building this project.

### Resources

- [Django](https://docs.djangoproject.com/en/5.0/)
- [Vue](https://vuejs.org/guide/introduction.html)
- [Tailwind](https://v2.tailwindcss.com/docs)

<p align="right">(<a href="#top">back to top</a>)</p>