# Recommendation Systems for Streaming Platforms

Lets understand and analyse the **Recommendation systems** used in streaming platforms.
In December of 2015, consumer research from Netflix estimated that a subscriber loses interest after 60 to 90 seconds of browsing before they choose something or abandon the streaming platform.
This is where algorithms step in.

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

| Use Case                                    | Algorithm                                          | Time Complexity                | Code                                                                         |
|---------------------------------------------|----------------------------------------------------|--------------------------------|------------------------------------------------------------------------------|
| Personalized Recommendation                 | Collaborative Filtering                            |                                |https://github.com/gorse-io/gorse                                             |
| Genre-based Suggestions                     | Content-Based Filtering                            |                                |https://github.com/vjvishaljha/Recommender_Sys                                |
| New Release Recommendation                  | Knowledge-Based Filtering                          |                                |https://github.com/xiangwang1223/knowledge_graph_attention_network            |
| Trending Content Discovery                  | Popularity-Based Filtering                         |                                |https://github.com/convenience-tinashe-chibatamoto/Movie-Recommendation-System|
| Seasonal Content Suggestion                 | Time-Based Filtering                               |                                |https://github.com/chen0040/mxnet-recommender                                 |
| User Engagement Optimization                | Reinforcement Learning                             |                                |https://github.com/fuxiAIlab/EOMM                                             |
| Multi-Modal Content Recommendation          | Multi-Modal Recommender Systems                    |                                |https://github.com/enoche/MultimodalRecSys                                    |
| Geo-Specific Recommendation                 | Geo-Based Filtering                                |                                |https://github.com/ustcml/GeoSAN                                              |
| Personal Playlist Curation                  | Sequential Recommendation                          |                                |https://github.com/SamU65/Celluliod-playlist-generator                        |
| User Retention/Churn Reduction              | Matrix Factorization with Side Information         |                                |https://github.com/rohitharitash/CustomerChurnReduction                       |
| Real-Time Content Updates and Notifications | Stream-based Collaborative Filtering               |                                |https://github.com/BaseMax/real-time-notifications-nats-go                    |
| User-Specific Advertisement Recommendation  | Context-Aware Recommender Systems                  |                                |https://github.com/rishikonapure/Advertisement-Recommendation                 |
| Diverse Content Exploration                 | Diversity-Aware Recommender Systems                |                                |https://github.com/guanghuixu/AnchorCaptioner                                 |
| Social Network Integration                  | Social Network-Based Filtering                     |                                |https://github.com/reddyprasade/Deep-Learning                                 |
