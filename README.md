<div id="top"></div>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/SolarSpec/Platform-Repo">
    <img src="PlatformRepo_resources/logo.png" alt="SolarSpec" width="160" height="120">
  </a>

<h3 align="center">Platform to House all SolarSpec Repositories</h3>

  <p align="center">
    Platform for all Code
    <br />
    <a href="https://github.com/SolarSpec/Platform-Repo"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/SolarSpec/Platform-Repo">View Demo</a>
    ·
    <a href="https://github.com/SolarSpec/Platform-Repo/issues">Report Bug</a>
    ·
    <a href="https://github.com/SolarSpec/Platform-Repo/issues">Request Feature</a>
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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
A repository to act as a platform to house all SolarSpec repositories. Intended for ease of use

<p align="right">(<a href="#top">back to top</a>)</p>



### Submodules Built With

* [MATLAB](https://www.mathworks.com/products/matlab.html)
* [TDMS Reader Addon](https://www.mathworks.com/matlabcentral/fileexchange/30023-tdms-reader)
* [Image Processing Toolbox](https://www.mathworks.com/help/images/)
* [Curve Fitting Toolbox](https://www.mathworks.com/help/curvefit/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Verify you have the necessary prequisites and follow the installation instructions.

### Prerequisites

Make sure MATLAB is installed. It is available for download in the Software Distribution section under the Help tab after you log into [Canvas.](https://canvas.ubc.ca/)
Click on the "Add-Ons" dropdown menu of your MATLAB Home screen. Then click on "Manage Add-Ons" and ensure you have the Image Processing Toolbox and the Curve Fitting Toolbox. If not, click on "Get Add-Ons" button instead and search for the aforementioned products.

### Installation

1. Clone the repo with each sub repository to your PC
   ```sh
   git clone --recurse-submodules https://github.com/SolarSpec/Platform-Repo.git
   ```
2. Specify which or install each application 
   ```
   Click on the .mlappinstall file in your repository to open and install in MATLAB
   ```
3. Browse the APPS header
   ```
   You will find the recently installed application and can add it to your favourites
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

To view the status of all repositories:
```sh
git status
```
and to view the status of each repository:
```sh
git submodule foreach git status
```

Pull changes for every submodule:
```sh
git submodule foreach git pull origin main
```
or in case you have edited the files and need to stash changes:
```sh
git submodule foreach git pull --rebase --autostash origin branch_name
```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap - GUIs/Repositories

- [X] Spectrabuilder
  - [X] Log-Log Fitting 
- [X] OnePanelFig
- [X] PIASgui
- [X] DLSmultiAverage
- [X] H2GUI
- [X] Electrochemistry
- [X] FTIR
- [X] OceanOptics
- [X] Photodegradation
- [X] TAMviewer
- [X] TaucPlotGUI
- [X] XPSfitting
- [X] XRDfitting

See the [open issues](https://github.com/SolarSpec/Platform-Repo/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the BSD 3-Clause License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

SolarSpec - [SolarSpec Website](https://solarspec.ok.ubc.ca/) - vidihari@student.ubc.ca

Project Link: [https://github.com/SolarSpec/Platform-Repo](https://github.com/SolarSpec/Platform-Repo)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Group Leader - Dr. Robert Godin](https://solarspec.ok.ubc.ca/people/)
* [Group Coder - Haris Vidimlic](https://solarspec.ok.ubc.ca/people/)
* [Group Coder - Mira Cuthill](https://solarspec.ok.ubc.ca/people/)
* [Group Alumni - James Kivai](https://solarspec.ok.ubc.ca/people/)
* [Group Alumni - Emma Mitchell](https://solarspec.ok.ubc.ca/people/)
* [Group Alumni - Jasper Pankratz](https://solarspec.ok.ubc.ca/people/)
* [The Entire SolarSpec Team](https://solarspec.ok.ubc.ca/people/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/SolarSpec/Platform-Repo.svg?style=for-the-badge
[contributors-url]: https://github.com/SolarSpec/Platform-Repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/SolarSpec/Platform-Repo.svg?style=for-the-badge
[forks-url]: https://github.com/SolarSpec/Platform-Repo/network/members
[stars-shield]: https://img.shields.io/github/stars/SolarSpec/Platform-Repo.svg?style=for-the-badge
[stars-url]: https://github.com/SolarSpec/Platform-Repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/SolarSpec/Platform-Repo.svg?style=for-the-badge
[issues-url]: https://github.com/SolarSpec/Platform-Repo/issues
[license-shield]: https://img.shields.io/github/license/SolarSpec/Platform-Repo.svg?style=for-the-badge
[license-url]: https://github.com/SolarSpec/Platform-Repo/blob/main/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/haris-vidimlic-06730019b/
[product-screenshot]: PlatformRepo_resources/Screenshot.png
