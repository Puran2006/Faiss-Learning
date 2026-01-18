
# INSTALLATION
Faiss works best with conda installation with all the dependencies resolved.
## First create a Environment :
```bash
conda create -n faiss-learn

# Activate the Environmet

conda activate faiss-learn
```
Install the packages
```
conda install -c pytorch faiss-cpu
conda install pandas numpy sentence-transformers
```

This is the Doc from where I started learning about faiss..I think it would be better to take a look at this whenever I need to reminded of how faiss works internally.
```
https://www.pinecone.io/learn/series/faiss/faiss-tutorial/
```

# TOPICS Covered
### Traditional Similarity Search
### Vector Based Similarty Search
### FAISS Introduction
### Product Quantization( PQ ) Understanding
### Inverted File PQ
### HNSW
### Metrics(Recall, MAP, NDCG)

### Filtering

To work with Filtering, you have to download datasets, easiest way is to pip install datasets

```
pip install datasets
```
```
https://www.pinecone.io/learn/vector-search-filtering/
```
```
pip install pinecone
```

Next create a .env file in the folder and add your pinecone there
```
PINECONE_API_KEY="yourPineConeKeyHere"
```

