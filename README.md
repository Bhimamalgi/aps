# Recommendation Systems for Streaming Platforms

Recommendation systems used in streaming platforms.

## Introduction

As streaming platforms have emerged as leading sources for entertainment media — particularly for [ﬁlm, television, music], access to content has increased to an overwhelming amount.

Actor Marc Maron theorizes that everyone had one person in their life that influenced their interests by introducing them to new films, music, books, clothes, or anything else. 
This person came to us at an influential time and changed the trajectory of our lives. That role is now being filled by algorithms.

- Amazon has been using recommendations from algorithms for its service since 1998.
- Netflix has been using algorithms for recommending entertainment since 2007 when it was only sending DVDs.
Now, all Streaming platforms use their algorithms alongside machine learning to guide the consumer to decide what to watch. They aim for - Increasing number of Subscribers
                            - Increasing viewing Hours
                            - Reducing Churn rate (Cancellation of service within threshold time)

The Recommendation systems can be broadly categorized into:

1. **Content-Based :** Recommends using metadata[tags, text] of items similar to those the user has interacted previously based on it's attributes.
2. **Collaborative Filtering :** Recommends content based on the preferences and behaviors of other users with similar tastes or behavioural pattern.
3. **Knowledge-Based :** Recommends by correlating explicit knowledge about user preferences and item attributes using their similarities. ( For discovery of new Content )

## Use Cases

### 1. Personalized Movie Recommendations
- **Algorithm:** Collaborative Filtering (e.g., Matrix Factorization)
- **Time Complexity:** O(nm), where n is the number of users and m is the number of items

### 2. Genre-based TV Show Suggestions
- **Algorithm:** Content-Based Filtering (using text features like plot summaries)
- **Time Complexity:** O(m), where m is the number of items

### 3. New Release Recommendations
- **Algorithm:** Knowledge-Based Filtering
- **Time Complexity:** O(1) for simple attribute matching

### 4. Trending Content Discovery
- **Algorithm:** Popularity-Based Filtering
- **Time Complexity:** O(n log n), where n is the number of items

### 5. Cross-Platform Recommendations
- **Algorithm:** Hybrid Recommender (Collaborative + Content-Based)
- **Time Complexity:** Varies based on specific algorithms used

### 6. Seasonal Content Suggestions
- **Algorithm:** Time-Based Filtering
- **Time Complexity:** O(n), where n is the number of items considered within the time window

### 7. User Engagement Optimization
- **Algorithm:** Reinforcement Learning
- **Time Complexity:** Depends on the RL algorithm used

### 8. Multi-Modal Content Recommendations
- **Algorithm:** Multi-Modal Recommender Systems
- **Time Complexity:** Depends on the complexity of feature extraction and fusion

### 9. Geo-Specific Recommendations
- **Algorithm:** Geo-Based Filtering
- **Time Complexity:** O(n), where n is the number of items considered within the geographical region

### 10. Personal Playlist Curation
- **Algorithm:** Sequential Recommendation
- **Time Complexity:** O(m), where m is the length of the sequence being recommended

### 11. User Retention and Churn Reduction
- **Algorithm:** Matrix Factorization with Side Information
- **Time Complexity:** O(nm), where n is the number of users and m is the number of items

### 12. Real-Time Content Updates and Notifications
- **Algorithm:** Stream-based Collaborative Filtering
- **Time Complexity:** O(n), where n is the number of active users or items in the stream

### 13. User-Specific Advertisement Recommendations
- **Algorithm:** Context-Aware Recommender Systems
- **Time Complexity:** O(m), where m is the number of items considered within the contextual parameters

### 14. Diverse Content Exploration
- **Algorithm:** Diversity-Aware Recommender Systems
- **Time Complexity:** O(n log n), where n is the number of items

### 15. Social Network Integration
- **Algorithm:** Social Network-Based Filtering
- **Time Complexity:** O(n), where n is the number of users or items influenced by social connections
