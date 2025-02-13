<p align="center">
  <h1 align="center">YALIJA</h1>

  <p align="center">
    Yet Another Lox Interpreter, written in Java.
  </p>
</p>

<div align="center">
  
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
  
</div>


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#features">Features</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

YALIJA stands for Yet Another Lox Interpreter written in Java. Initially I wanted to claim that it's "a new programming language written in Java" because it sounds cooler :p, but it's not.

Lox is a programming language defined in Bob Nystrom's book, [Crafting Interpreters](http://craftinginterpreters.com/). It's a language created for learning purpose only, and not used in real industry-standard environment like Java, Python, or any other major programming language does.

As for this interpreter, it's a tree-walking interpreter, which kicks up the core interpreter right after parsing is done, it walks through the AST while evaluating each node as it goes through. There's no compilation step, no bytecode generation, let alone machine code generation or any similar fancy stuff.
According to the original author, it's relatively slow performance-wise, but I don't think it matters, it's a great start for learning.

### Why I built this

I've always had this vague curiosity about how things works under the hood. Especially in software engineering, since we got all these amazing tools, frameworks,
and programming languages popping up every so often. And upon realizing that most of these tools are hand-crafted by programmers, it kind of provoked my
curiosity.

And one thing I'm always curious about is how programming languages are made, since programming language is the very fundamental building block 
to every tool that exists today, and it's also a thing every programmer uses on a day-to-day basis. Thankfully I stumbled upon Bob Nystrom's [craftinginterpreters.com](https://craftinginterpreters.com) which provides a very valuable guidance for free.

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

You need to have JDK 11 or later installed on your computer. There are many flavors of JDK and tutorials online to guide you if you don't know how to install it, 
you can simply google it. Or you can go [here](https://www.oracle.com/java/technologies/javase-downloads.html) if you're unsure.

### Installation

Go to the [releases page](https://github.com/danilhendrasr/yalija/releases) and download the latest release's jar. Then run it in your terminal, with the following command,
```bash
java -jar yalija-x.x.x-release-name.jar
```

The above command will run yalija in REPL mode. If you wanted to run a file, run the following command,
```
java -jar yalija-x.x.x-release-name.jar hello_world.lox
```

## Features

_Documentation coming up soon_


<!-- LICENSE -->
## License

Distributed under the MIT License. See [LICENSE](https://github.com/danilhendrasr/yalija/blob/main/LICENSE) for more information.


<!-- CONTACT -->
## Contact

Danil Hendra Suryawan - danilhendrasr@gmail.com


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [craftinginterpreters.com](https://www.craftinginterpreters.com)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/danilhendrasr/yalija.svg?style=for-the-badge
[stars-url]: https://github.com/danilhendrasr/yalija/stargazers
[issues-shield]: https://img.shields.io/github/issues/danilhendrasr/yalija.svg?style=for-the-badge
[issues-url]: https://github.com/danilhendrasr/yalija/issues
[license-shield]: https://img.shields.io/github/license/danilhendrasr/yalija.svg?style=for-the-badge
[license-url]: https://github.com/danilhendrasr/yalija/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/danilhendrasr
[product-screenshot]: images/screenshot.png
