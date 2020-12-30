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
  <a href="https://github.com/Djensonsan/Spotify_Challenge">
    <img src="images/deep-learning.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Spotify Sequential Skip Prediction Challenge</h3>

  <p align="center">
    A collection of notebooks for tackling the Spotify Skip Prediction Challenge.
    <br />
    <a href="https://www.aicrowd.com/challenges/spotify-sequential-skip-prediction-challenge">Challenge Description</a>
    ·
    <a href="https://github.com/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge/issues">Report Bug</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

Based on the skipping behavior of users, Spotify seeks to improve its music recommendation engine. 
From an academic standpoint, the Spotify Skip Prediction Challenge offered a unique opportunity for researchers to improve and design state-of-the-art machine learning algorithms using a large, real-world dataset.
The concrete goal of the challenge was to predict whether a listener will skip a certain song or not. After the challenge was concluded in early 2019, the top-performing teams were invited to write papers about how they tackled the challenge. These top-performing teams used the following ideas:
* Feature Engineering
* Embeddings
* Recurrent Neural Networks

This project contains some notebooks you could use to get started on the Spotify Skip Prediction Challenge yourself.

## Results
More information can be found in following pdf document describing the challenge and our results: [Spotify_Challenge_Report](https://github.com/Djensonsan/Spotify_Challenge).

### Built With
* [Google Colab](https://colab.research.google.com/)
* [Tensorflow](https://www.tensorflow.org/)

<!-- GETTING STARTED -->
## Getting Started

### Installation
In order to run the notebooks, you can either use a Jupyter Notebook server or Google Colab. 
Note: to run these notebooks on a Jupyter Notebook server some small changes might have to be made.

1. Create a Google Colab account
2. Go to: [Colab Notebooks](https://colab.research.google.com/notebooks/intro.ipynb)
3. Click open notebook and choose Github
4. You should be able to search for an organisation or user
5. Choose a notebook you want to open

### Notebook Overview
* [exploration](https://github.com/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge/tree/main/exploration/): contains some data wrangling and a simple regression classifier. Also contains some exploratory code, PCA analysis etc.
* [pre-trained-embedding](https://github.com/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge/tree/main/pre-trained-embedding): contains a notebook for training a Word2Vec embedding, the track IDs are the 'words'.
* [similarity measures](https://github.com/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge/tree/main/similarity-measures/): contains a notebook that will calculate the mahalanobis distance between a track's vectors and the mean representation of tracks in the same session.
* [RNN](https://github.com/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge/tree/main/models): contains an RNN model based on LSTM networks. 


<!-- USAGE EXAMPLES -->
## Usage
As can be seen in the notebooks, the larger datasets are stored on the Cloud.
You can download the data yourself here: [Spotify Sequential Skip Prediction Challenge](https://www.aicrowd.com/challenges/spotify-sequential-skip-prediction-challenge).

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Seen a bug?

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

Jens Leysen - Jens.Leysen@student.uantwerpen.be

Project Link: [https://github.com/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge](https://github.com/Djensonsan/Spotify_Challenge_Report.pdf)

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* <div>Logo made by <a href="https://www.flaticon.com/authors/becris" title="Becris">Becris</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge.svg?style=flat-square
[contributors-url]: https://github.com/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge.svg?style=flat-square
[forks-url]: https://github.com/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge/network/members
[stars-shield]: https://img.shields.io/github/stars/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge.svg?style=flat-square
[stars-url]: https://github.com/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge/stargazers
[issues-shield]: https://img.shields.io/github/issues/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge.svg?style=flat-square
[issues-url]: https://github.com/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge/issues
[license-shield]: https://img.shields.io/github/license/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge.svg?style=flat-square
[license-url]: https://github.com/Djensonsan/Spotify-Sequential-Skip-Prediction-Challenge/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/jens-leysen
