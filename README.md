[![Mastodon](https://img.shields.io/badge/Mastodon-5c4bdf?style=for-the-badge&logo=Mastodon&logoColor=ffffff&link=https://fosstodon.org/@hya)](https://fosstodon.org/@hya)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=LinkedIn&logoColor=ffffff&link=https://www.linkedin.com/in/yahya-chahine/)](https://www.linkedin.com/in/yahya-chahine/)
[![Portfolio](https://img.shields.io/badge/Portfolio-6366f1?style=for-the-badge&logo=Internet-Explorer&logoColor=ffffff&link=https://www.chahineyahya.dev)](https://www.chahineyahya.dev)

# Correlation between Musical Notes and Socio-Political Events

## Project Purpose

This research work was conducted during my Master's degree final project, it aims to reproduce a previous research conducted in part by supervisor Prof.
Choi-Hong Lai, on a different country and using a bigger dataset where I investigated the potential correlation between musical notes played in popular music and socio-political events, election results in this case.

## Analysis

The dataset for this project was provided to me by my supervisor in the form of 700 `.au` audio files categorized by genre:

- Blues
- Classical
- Country
- Disco
- Jazz
- Pop
- Rock

The Analysis phase consisted of a extracting 6 signal processing features from each of the 700 audio files and feeding them to 2 Supervised
Machine Learning algorithms i.e. K Nearest Neighbour and Support Vector Machine and comparing the performances of each one of them.

## Setup

The project was setup using pypev and pipenv and is fairly simple to setup locally, unfortunately however, the musical files are way too large
to be stored on GitHub or Drive and I as of now have no way to link them. (This may change in the future).

- Start by cloning the repo.

```console
git clone git@github.com:ceeyahya/lichess-games-analysis.git
```

- Create a virtual environment with the your favourite utility.

- Install the dependencies.

```console
pipenv install
```

- Start running the code.

## Dataset

The dataset was provided to me by my Supervisor.
