<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
![Hireable](https://cdn.rawgit.com/hiendv/hireable/master/styles/default/yes.svg)

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/euqueme/toy-app">
    <img src="app/assets/images/mLogo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Toy App</h3>

  <p align="center">
    This project is part of the Microverse Ruby on Rails curriculum!
    <br />
    <a href="https://github.com/euqueme/toy-app"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://rails-toy-app-audreynmaru.herokuapp.com/">View Demo</a>
    ·
    <a href="https://github.com/euqueme/toy-app/issues">Report Bug</a>
    ·
    <a href="https://github.com/euqueme/toy-app/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
  * [Usage](#usage)
  * [Live Demo](#live-demo)
  * [Automated Test](#automated-test)
* [Author](#author)
* [Contributing](#contributing)
* [Acknowledgements](#acknowledgements)

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://rails-toy-app-audreynmaru.herokuapp.com/)

This is the first Microverse project of the Ruby on Rails Curriculum

This is also part of the Odin project curriculum https://www.theodinproject.com/courses/ruby-on-rails/lessons/getting-your-feet-wet

And the second chapter of the Learn enough to be dangerous tutorial https://www.learnenough.com/ruby-on-rails-4th-edition-tutorial/toy_app#sec-planning_the_application

### Built With
This project was built using these technologies.
* Ruby 2.5.7
* Rails 6.0.1
* Windows 10
* Kali Linux
* Stickler
* VsCode
* Notepad++

<!-- ABOUT THE PROJECT -->
### Usage

If you want to test it you need to have Ruby and Rails installed in your computer and [download](https://github.com/euqueme/toy-app/archive/master.zip) or clone this repo as follows:
* `$ git clone "https://github.com/euqueme/toy-app.git"`

after that you need to open a terminal inside the repo and run the bundler
* `$ bundle  install --without production`

then, run rails db:migrate. This creates the database with the corresponding tables, columns and associations.
* `$ rails db:migrate`

and finally, you can test it in the console using the sandbox with the following command
* `$ rails server`

If no errors were displayed open a browser in your [localhost](http://localhost:3000/) and you should be able create new users, edit and destroy them 


![screenshot](app/assets/images/toy_app_users.png)

If you want to create new microposts, edit or destoy them you have to go to the [microposts](http://localhost:3000/microposts) page

![screenshot](app/assets/images/toy_app_microposts.png)

<!-- LIVE VERSION -->
### Live Demo

You can see it working here:  https://rails-toy-app-audreynmaru.herokuapp.com/

<!-- AUTOMATED TEST -->
### Automated Test

> There are no Automated Test for this project yet

<!-- CONTACT -->
## Author

👤 **Audrey Emmanuella Odiaka** 
- Twitter: [@o___audrey_xo](https://twitter.com/o___audrey_xo) 
- Github: [@audrey-ella-xo](https://github.com/audrey-ella-xo) 
- Gmail: anitaudrey@gmail.com

👤 **María Eugenia Quemé** 

- Twitter: [@MaruKK](https://twitter.com/MaruKK) 
- Github: [@euqueme](https://github.com/euqueme) 
- Gmail: euqueme@gmail.com

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/euqueme/micro-reddit/issues).

## Show your support

Give a ⭐️ if you like this project!

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Microverse](https://www.microverse.org/)
* [The Odin Project](https://www.theodinproject.com/)
* [Learn enough to be dangerous Ruby on Rails Tutorial](https://www.learnenough.com/ruby-on-rails-4th-edition-tutorial/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/euqueme/toy-app.svg?style=flat-square
[contributors-url]: https://github.com/euqueme/toy-app/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/euqueme/toy-app.svg?style=flat-square
[forks-url]: https://github.com/euqueme/toy-app/network/members
[stars-shield]: https://img.shields.io/github/stars/euqueme/toy-app.svg?style=flat-square
[stars-url]: https://github.com/euqueme/toy-app/stargazers
[issues-shield]: https://img.shields.io/github/issues/euqueme/toy-app.svg?style=flat-square
[issues-url]: https://github.com/euqueme/toy-app/issues
[product-screenshot]: app/assets/images/screenshot.PNG
