{\rtf1\ansi\ansicpg1252\cocoartf1671\cocoasubrtf600
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 Aim of this work is to recognise the text from images in terms of character and word levels.\
\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\
\
The dataset used here contains images of each hand-written words with the dash-separated filename format. The first field represents word id, second the result of word segmentation, third graylevel to binarize the line containing the word, fourth bounding box around the word, fifth grammatical tag, sixth the transcription for the word.
\fs28 \expnd0\expndtw0\kerning0
\

\fs24 \kerning1\expnd0\expndtw0 \
Dataset was downloaded from this link \'93http://www.fki.inf.unibe.ch/databases/iam-handwriting-database/download-the-iam-handwriting-database\'94 (data/words)\
\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\
\
Model: Blend of convolutional neural network and Sequence to sequence modelling with LSTM / GRU\
\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\
\
Notebooks:\
\
Sequence2Sequence_LSTM.ipynb:\
\
	Results: true word recognition: 45%\
	              character recognition: 42%\
\
Sequence2Sequence_GRU.ipynb:\
\
	Results: true word recognition: 55%\
	      	     character recognition: 49%\
\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\'97\
\
Reference: https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html\
}