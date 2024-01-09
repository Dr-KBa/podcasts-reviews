# Inferential Statistical Analysis
This notebook called "Project M2S2" is part of the Turing College assignment of Module 2 Sprint 2. It can be used as a standalone file for analysis and data files preparation for Google Looker Studio. However, dataset from kaggle.com must be downloaded manually. This dataset contains a large SQLite database (over 800 MB).

# Project description
This project contains the analysis of Podcast reviews: 2 million podcast reviews for 100k podcasts, updated monthly. This dataset is intended to aid in analysis of text feedback and review data.

The aim of this analysis is to explore user behaviour and provide useful insights backed by statistical methods.

Part of the analysis can be accessed at Google Looker Studio (pdf file also included in GitHub repository of this project): lookerstudio.google.com/s/qlQCnH9WKFU

# Data download
"Podcast Reviews" dataset must be downloaded from (under License CC BY-NC-SA 4.0):
https://www.kaggle.com/datasets/thoughtvector/podcastreviews/versions/28

# Packages
Required packages are listed in "Project M2S2" notebook. It should be noted that "textblob" package takes a long time (up to 5 min) to calculate sentiment scores for over 2M reviews. If uninterrupted, scoring always finishes successfully. 

# Contribution
The analysis was made by Kazimieras Badokas, parts of the code was suggested/autocompleted by ChatGPT and GitHub Copilot, code was autoformatted using nb_black extension.

# License
MIT License for analysis

Copyright (c) [2023] [Kazimieras Badokas]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

BY-NC-SA 4.0 License for initial dataset!



