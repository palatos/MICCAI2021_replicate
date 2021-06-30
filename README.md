<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo_name, twitter_handle, email, project_title, project_description
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
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/maragraziani/MICCAI2021_replicate">
    <img src="images/logo.png" alt="Logo" width="700">
  </a>

  <h3 align="center">Sharp-LIME: Sharpening Local Interpretable Model-agnostic Explanations for Histopathology</h3>

  <p align="center">
    Applying off-the-shelf methods with default configurations such as Local Interpretable Model-Agnostic Explanations (LIME) [1] is not sufficient to generate stable and understandable explanations in histopathology. 
This work improves standard LIME by leveraging nuclei annotations, creating a reliable way for pathologists to audit black-box tumor classifiers.
The obtained visualizations reveal the sharp, neat and  high attention of the deep classifier to the neoplastic nuclei in the dataset, an observation in line with clinical decision making. Compared to standard LIME, our explanations show improved understandability for domain-experts, report higher stability and pass the sanity checks of consistency to data or initialization changes and sensitivity to network parameters. 
    <br />
    <a href="https://github.com/maragraziani/MICCAI2021_replicate"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/maragraziani/MICCAI2021_replicate/notebooks">View Examples</a>
    ·
    <a href="https://github.com/maragraziani/MICCAI2021_replicate/issues">Report Bug</a>
    ·
  </p>
</p>


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Based Upon</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Paper
This 

### Based Upon

* [1]() Local Interpretable Model-agnostic Explanations
* [2]() Iam work
* [3]() Evaluation XAI2021

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This code was developed in Python 3.6 and using Tensorflow 2. You will also need some standard packages to replicate the experiments.Follow the instructions in **Installation** to set the environment 

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/maragraziani/MICCAI2021_replicate
   ```
2. Install python packages with pip
  
  ```sh
  pip install numpy pandas matplotlib h5py seaborn scikit-image 
  pip install git+https://github.com/palatos/lime@ColorExperiments
  ```

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Notebooks](https://github.com/maragraziani/MICCAI2021_replicate/notebooks) folder

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact

Mara Graziani - [@mormontre](https://twitter.com/mormontre) - mara.graziani@hevs.ch
Iam Palatnik - iam.palat@gmail.com

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* []()
* []()
* []()




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/maragraziani/MICCAI2021_replicate.svg?style=for-the-badge
[contributors-url]: https://github.com/maragraziani/MICCAI2021_replicate/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/maragraziani/MICCAI2021_replicate.svg?style=for-the-badge
[forks-url]: https://github.com/maragraziani/MICCAI2021_replicate/network/members
[stars-shield]: https://img.shields.io/github/stars/maragraziani/MICCAI2021_replicate.svg?style=for-the-badge
[stars-url]: https://github.com/maragraziani/MICCAI2021_replicate/stargazers
[issues-shield]: https://img.shields.io/github/issues/maragraziani/MICCAI2021_replicate.svg?style=for-the-badge
[issues-url]: https://github.com/maragraziani/MICCAI2021_replicate/issues
[license-shield]: https://img.shields.io/github/license/maragraziani/MICCAI2021_replicate.svg?style=for-the-badge
[license-url]: https://github.com/maragraziani/MICCAI2021_replicate/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/mara-graziani-878980105/
