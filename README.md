{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf600
{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fnil\fcharset0 Menlo-Regular;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red255\green255\blue255;}
{\*\expandedcolortbl;;\csgray\c0;\csgray\c100000;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 To fetch data from guardian api use the following command.\
\
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardirnatural\partightenfactor0

\f1\fs22 \cf2 \cb3 \CocoaLigature0 usage: fetch_data.py [-h] -f FROM_DATE -t TO_DATE [-c CATEGORY] -p PATH_TO_DIR\
\
optional arguments:\
  -h, --help            show this help message and exit\
  -f FROM_DATE, --from_date FROM_DATE\
                        From date\
  -t TO_DATE, --to_date TO_DATE\
                        To date\
  -c CATEGORY, --category CATEGORY\
                        Category to fetch, if not mentioned all categories\
                        will be fetched\
  -p PATH_TO_DIR, --path_to_dir PATH_TO_DIR\
                        Path to directory to save the files\
\
\
To train the model use the following command.\
\
\
To train a model set using any of the configuration file and run the following command.\
\
usage: python main.py -c configs/<any config file>\
\
example:\
python main.py -c configs/BiLSTM_model_title.json}
