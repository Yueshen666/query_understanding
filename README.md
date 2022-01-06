# query_understanding 

# Query Understanding Topics
## I. Spelling Correction
An improved noisy channel model: https://aclanthology.org/D09-1093.pdf

## II. Query Rewritting

### 1. Query Segmentation
a. Statistical Approach (including word2vec)
b. Similar to semantic sequential labeling: also can use other tags: NER, POS, etc.
### 2. Query Expansion
### 3. Query Relaxation
### 4. Query Scoping
"red canada goose coat" (B-color,B-brand,I-brand,B-product)

## III. Query Understanding by Facets
good use for autocompletion and query rewritting
## IV. Session-based Models
info about recent clicks/refinement 
`pseudo relevance feedback` simulates relevance feedback by reinforcing the top-ranked results as if the searcher had provided positive relevance feedback for them.
## V. Personalization
info about demographics - autocompletion
## VI. Query Auto Completion (QAC)
Most popular completion: lookup recent query history matching prefix input
Generative Models: prob n-gram/LM w/o log
