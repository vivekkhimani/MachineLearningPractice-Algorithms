# Gender Classification Problem using names

# Purposei:
- This proect was done to solve one of the problems we faced while building our product for the DragonHacks2020. For DragonHacks 2020, we built an interface which used Twitter API to match the users with their second connections. As gender was a primary requirement for filtering out the recommendation, I built this LSTM model to solve the problem.

# Approach:
- Because the determination of gender using names depends on sequence and context of the previous characters, I used a Bidirectional LSTM to store the context. The base model yielded above 80% accuracy on validation set. To further improve it, I optimized my training set vectorization and produced more efficient word-embeddings by One-Hot Encoding individual characters and also mapping down the null characters to a fixed length string. After the optimization I achieved 90%+ overall acccuracy.

# Completion Time:
- The entire building and optimization process took less than 4 hours.
