# ClassicalArtMemes

Classical Art Memes were examined in this project. The structure of the repository will now be explained.

## 2015 - 2022

The following files can be found in the folders from 2015 to 2022:
- A CSV file with the meta-data of the year/ a CSV file where the OCR text is preprocessed.
- an image of the visual barcode of the year
- an image of the POS distribution
- an image of the NE
- an image of the most frequently used words and a corresponding word cloud
- a wordcloud to the titles of the reddit posts

## Code

In this folder the Jupyter Notebooks can be found, which were used for the download of the data/images, for the cleaning of the data and for the analysis of the data.

## Presentation

This folder contains the initial presentation and the final presentation of the project.

## Research Paper

This folder contains the research paper of this project.

## all_csv_images

Three CSV files can be found in this folder:
- `all_data_all_images_no_duplicates.csv` : In this CSV file the data set is cleaned, but OCR is not performed yet.
- `ocr_google_vision.csv`: In this CSV file OCR has been performed, so duplicates in the dataset have been noticed, which were not visible before.
- `filtered_file_ocr_no_duplicates.csv`: All duplicates were removed. The analyses were performed with this data set.

## all_raw_csv

TwoCSV files can be found in this folder:
- `filtered_file_no_images_no_duplicates.csv`: In this CSV file the raw data was filtered for the first time. This was used to download the images.
- `trippinthroughtime_data_all_years.csv`: In this CSV file all raw data was saved.

## statistics

This folder contains images of the analyses that have been performed:
- `allgemeine_Analyse.png`: Image file that contains a general analysis of the data set.
- `awards_stats.png`: Image file that contains statistics on the number of awards received by posts.
- `brightness.png`: Image file that contains brightness analysis of the images in the data set.
- `comments_stats.png`: Image file that contains statistics on the number of comments received by posts.
- `crossposts_stats.png`: Image file that contains statistics on the number of crossposts received by posts.
- `image_count_year.png`: Image file that contains a graph showing the number of images posted per year.
- `score_stats.png`: Image file that contains statistics on the scores received by posts.
- `sentiment_analysis.png`: Image file that contains sentiment analysis of the posts in the data set.
- `subscribers_stats.png`: Image file that contains statistics on the number of subscribers to the subreddit over time.