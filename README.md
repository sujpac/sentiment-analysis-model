# Film Review Sentiment Analysis Model

## Background
We will be using the [IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/)
> Maas, Andrew L., et al. [Learning Word Vectors for Sentiment Analysis](http://ai.stanford.edu/~amaas/data/sentiment/). In _Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies_. Association for Computational Linguistics, 2011.


## Outline
1. Download or otherwise retrieve the data.
2. Process / Prepare the data.
3. Upload the processed data to S3.
4. Train a chosen model.
5. Test the trained model (typically using a batch transform job).
6. Deploy the trained model.
7. Use the deployed model.

### Step 1: Download the data

'''sh
"%mkdir ../data\n",
"!wget -O ../data/aclImdb_v1.tar.gz http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz\n",
"!tar -zxf ../data/aclImdb_v1.tar.gz -C ../data"
'''

### Step 2: Process the data

### Step 3: Upload the data to S3

### Step 4: Train the model

### Step 5: Test the model

### Step 6: Deploy the model

### Step 7: Use the model
