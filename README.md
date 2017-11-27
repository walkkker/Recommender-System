# Recommender-System(RecSys)

### Quickly check:<br/>
[wiki-Recommender System](https://en.wikipedia.org/wiki/Recommender_system)<br/>
[Stanford-Recsys Chapter 9](http://infolab.stanford.edu/~ullman/mmds/ch9.pdf)

### Brief Summary:
RecSys: to recommend the *appropriate* items to the *potential* users who are likely to buy, subscribe, listen, watch...<br/>

### Approaches: 
1. **Content-based**: A content-based system is to recommend items that are similar to those that a user liked in the past, and it is based on item description and a profile of the users' preferences.<br/>
for example: item features --> tf-idf --> Build model based on users' past interaction/preference.<br/>
2. **Collaborative filtering(CF)**: Predicting users' preference based on their similarity to others by analyzing their behaviors, past activities or preferences. Note that it does not analyze item content.
   2.1. Two forms of data:
       * explicit feedback
       * implicit feedback
   2.2. Two primary areas:
       * neighborhood methods
       * latent factor models
   2.3. Three Challenges in CF
       * Cold start: new users and/or items
       * Scalability: future item expansion
       * Sparsity: low user-item interaction. Users only hold a few out of tons of items.
<br/>
3. **Hybrid RecSys**: Combine Content-based and CF and can be implemented in several ways.

