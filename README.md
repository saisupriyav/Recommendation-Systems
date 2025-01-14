Building on our recommendation system using cosine similarity, we’ve enhanced our approach by incorporating transaction data to suggest items commonly purchased together. 
This expanded system provides not only similar products but also relevant co-purchases, creating a more comprehensive recommendation experience.

Process Overview:

Cosine Similarity Calculation: Using cosine similarity, we quantified the similarity between articles, enabling us to identify products closely related to the chosen article.

Co-purchase Analysis: Using transaction data, we identified items frequently bought together, which adds a practical relevance layer beyond similarity alone.

Combined Recommendations: We now suggest a blend of 12 items—8 based on cosine similarity and 4 from co-purchase patterns—ensuring that customers receive well-rounded suggestions 
reflective of both item features and actual purchase behavior.

Overall, this notebook showcases a foundational yet effective method for personalized recommendations in retail. By combining content-based and co-purchase recommendations, 
we offer a more personalized shop ping experience, aligning suggestions with both product similarities and popular customer pairings. This approach supports cross-selling 
while making the recommendation system more engaging and useful for the customer.
