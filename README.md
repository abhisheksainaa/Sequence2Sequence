Aim of this work is to recognise the text from images in terms of character and word levels.
—————————————————————————————————————————————

The dataset used here contains images of each hand-written words with the dash-separated filename format. The first field represents word id, second the result of word segmentation, third graylevel to binarize the line containing the word, fourth bounding box around the word, fifth grammatical tag, sixth the transcription for the word.

Dataset was downloaded from this link “http://www.fki.inf.unibe.ch/databases/iam-handwriting-database/download-the-iam-handwriting-database” (data/words)
—————————————————————————————————————————————

Model: Blend of convolutional neural network and Sequence to sequence modelling with LSTM / GRU
—————————————————————————————————————————————

Notebooks:

Sequence2Sequence_LSTM.ipynb:

	Results: true word recognition: 45%
	         character recognition: 42%
	         
Sequence2Sequence_Bi-LSTM.ipynb:

	Results: true word recognition: 50%
			 character recognition: 46%

Sequence2Sequence_Bi-GRU.ipynb:

	Results: true word recognition: 55%
			 character recognition: 47%
			 
Sequence2Sequence_GRU.ipynb:

	Results: true word recognition: 55%
	      	 character recognition: 49%
	      	 
—————————————————————————————————————————————

Reference: https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html