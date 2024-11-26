**Hybrid Recommendation Algorithm using MovieLens 100k Dataset:**

*Basic information:*
- Dataset used: Movielens 100k data
- Type of recomendation model: Combination of SVD + Content-based filtering

*Why this approach?*

- Using a weighted hybrid system combining Content-filtering and Matrix Factorization Techniques to build off the limitations of both algorithms, to provide more accurate recommendations to the user
- Strengths of SVD: 
    - Good at understanding user-item iteraction relationships 
    - Offers the component of user-personalization
    
- Strengths of Content-based: 
    - Does not rely on user-item iteractions
    - Recommends movies based upon move metadata (e.g. genres)
    - Can avoid popularity bias
    
- Using both:
    - Allows for the system to recommend movies based on both the user-item relationships as well as the metadata of the movies
    - Mix of user personalization + exact metadata preferences 
