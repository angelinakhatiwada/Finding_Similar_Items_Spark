# Finding Similar Items using Spark

#### The objective of this project is to detect pairs of similar items in the ”StackSample” dataset.

Spark environment was set to run computations and scale the results. The following modules were explored:
- **Spark SQL**, a relational framework for structured data processing
- **Spark MLlib**, a scalable machine learning library for feature extraction and similarity analysis

**Dataset**: 

The project consists of:

*1. Exploratory analysis and Data pre-processing*:
- Creating PySpark dataframe
- Missing and unique values check
- Duplicate values check
- Text pre-processing

*2. Feature Extraction:*
- TF (HashingTF applied)
- TF-IDF

*3. Similarity analysis:*
- Locality sensitive hashing for approximate similarity join (MinHash with Jaccard distance applied)
- Cosine similarity join (inner product of feature vectors)

*4. Performance comparison* in terms of computation speed and ability to detect similar pairs.
