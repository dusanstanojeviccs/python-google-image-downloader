# python-google-image-downloader

### Setup

This repo represents a simple jupyter notebook for downloading images from the Google Image Search. The notebook uses the chrome selenium webdriver to get the google images. To run this notebook you must make sure you have Chrome installed and that you have the correct chromedriver (the one that matches your version of Chrome) located in the same repository as this notebook file. More info is available on https://chromedriver.chromium.org/downloads.

The current chromedriver file in this git repository is for macOS and it was used with Chrome version 79.0.3945.88, to figure out your version of chrome you can go to chrome://version/.

### Configuration

To change the search query make sure you change the variable ```query```, if you want to change the path for the images you are downloading change the variable ```class_name```.

To change how many images you would like to download change the variable ```image_count```. 

To change the maximum number of tries to load more images before if the image_count has not been reached you can change the variable ```max_loops_with_no_images```.

If you run the scrip without changes it will download images of cats by running the search for the keyword "cat" into the "cat" folder.

### Contribute

Feel free to file issues on github, open pull requests with improvements, or reach out with suggestions to dusan.stanojevic.cs@gmail.com.

