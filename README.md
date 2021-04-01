# SparkSolution
 Spark code to process data from the Amazon and Netflix databases to perform analysis and comparisons of films from the two platforms.

## Package Version

	Run 'pip install -r requirements.txt'. The requirements.txt must be in project root directory.
	The version used in this project is 'Java OpenJDK 11.0.10'.

## Datasets to run the code

1. Download Amazon Dataset
Download the Amazon data from https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Digital_Video_Download_v1_00.tsv.gz and unzip the file.
For more info about this dataset consult: https://s3.amazonaws.com/amazon-reviews-pds/readme.html

2. Download Netflix dataset
Download Netflix dataset from https://www.kaggle.com/netflix-inc/netflix-prize-data  and unzip the file. You also can download the files:

combined_data_1.txt
combined_data_2.txt
combined_data_3.txt
combined_data_4.txt
movie_titles.csv

one by one and put then in the same file.

3. Properly configure in code the paths to where the downloaded folders are.
	
If all folders are in the same directory as the notebook and the ones named "netflix_reviews" for netflix data and  "amazon_reviews_us_Digital_Video_Download_v1_00" for Amazon data, the notebook should run without having to change the paths.

### Files Struct
	Spark_code_Amazon_Netflix_Analisys
	│
	│
	├─── DesafioSolvimSpark.ipynb
	│
	├─── netflix_reviews
	│	 │
	│	 ├─── combined_data_1.txt
	│	 │
	│	 ├─── combined_data_2.txt
	│	 │
	│	 ├─── combined_data_3.txt
	│	 │
	│	 ├─── combined_data_4.txt
	│	 │
	│	 └─── movie_titles.csv
	│
	│
	│
	└──── amazon_reviews_us_Digital_Video_Download_v1_00
		│	
		└─ amazon_reviews_us_Digital_Video_Download_v1_00.tsv
		