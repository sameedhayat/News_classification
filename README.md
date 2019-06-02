# Crawling Literature and classifying them with Natural Language Processing

One Paragraph of project description goes here

## Getting Started

usage: fetch_data.py [-h] -f FROM_DATE -t TO_DATE [-c CATEGORY] -p PATH_TO_DIR

optional arguments:
  -h, --help            show this help message and exit
  -f FROM_DATE, --from_date FROM_DATE
                        From date
  -t TO_DATE, --to_date TO_DATE
                        To date
  -c CATEGORY, --category CATEGORY
                        Category to fetch, if not mentioned all categories
                        will be fetched
  -p PATH_TO_DIR, --path_to_dir PATH_TO_DIR
                        Path to directory to save the files


To train the model use the following command.

To train a model set using any of the configuration file and run the following command.

usage: python main.py -c configs/<any config file>

example:
python main.py -c configs/BiLSTM_model_title.json

## Methodology
![Alt text](images/methodology.png "Methodology")
