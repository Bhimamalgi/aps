# Recommendation Systems for Streaming Platforms

Let's understand and analyze the **Recommendation systems** used in streaming platforms. In December of 2015, consumer research from Netflix estimated that a subscriber loses interest after 60 to 90 seconds of browsing before they choose something or abandon the streaming platform. This is where algorithms step in.

## Introduction

As streaming platforms have emerged as leading sources for entertainment media — particularly for [ﬁlm, television, music], access to content has increased to an overwhelming amount.

Actor Marc Maron theorizes that everyone had one person in their life that influenced their interests by introducing them to new films, music, books, clothes, or anything else. This person came to us at an influential time and changed the trajectory of our lives. That role is now being filled by algorithms.

- Amazon has been using recommendations from algorithms for its service since 1998.
- Netflix has been using algorithms for recommending entertainment since 2007 when it was only sending DVDs.

Now, all streaming platforms use their algorithms alongside machine learning to guide the consumer to decide what to watch. They aim for:
- Increasing number of Subscribers
- Increasing viewing Hours
- Reducing Churn rate (Cancellation of service within threshold time)

The recommendation systems can be broadly categorized into:

1. **Content-Based:** Recommends using metadata [tags, text] of items similar to those the user has interacted previously based on its attributes.
2. **Collaborative Filtering:** Recommends content based on the preferences and behaviors of other users with similar tastes or behavioral patterns.
3. **Knowledge-Based:** Recommends by correlating explicit knowledge about user preferences and item attributes using their similarities. (For discovery of new content)

## Use Cases

| #  | Use Case                                    | Algorithm                                          | Time Complexity                | Details                    |
|----|---------------------------------------------|----------------------------------------------------|--------------------------------|----------------------------|
| 1  | Personalized Recommendation                 | Collaborative Filtering                            |                                | [Details](./details/1.md)  |
| 2  | Genre-based Suggestions                     | Content-Based Filtering                            |                                | [Details](./details/2.md)  | 
| 3  | New Release Recommendation                  | Knowledge-Based Filtering                          |                                | [Details](./details/3.md)  |
| 4  | Trending Content Discovery                  | Popularity-Based Filtering                         |                                | [Details](./details/4.md)  |
| 5  | Seasonal Content Suggestion                 | Time-Based Filtering                               |                                | [Details](./details/5.md)  |
| 6  | User Engagement Optimization                | Reinforcement Learning                             |                                | [Details](./details/6.md)  |
| 7  | Multi-Modal Content Recommendation          | Multi-Modal Recommender Systems                    |                                | [Details](./details/7.md)  |
| 8  | Geo-Specific Recommendation                 | Geo-Based Filtering                                |                                | [Details](./details/8.md)  |
| 9  | Personal Playlist Curation                  | Sequential Recommendation                          |                                | [Details](./details/9.md)  |
| 10 | User Retention/Churn Reduction              | Matrix Factorization with Side Information         |                                | [Details](./details/10.md) |
| 11 | Real-Time Content Updates and Notifications | Stream-based Collaborative Filtering               |                                | [Details](./details/11.md) |
| 12 | User-Specific Advertisement Recommendation  | Context-Aware Recommender Systems                  |                                | [Details](./details/12.md) |
| 13 | Diverse Content Exploration                 | Diversity-Aware Recommender Systems                |                                | [Details](./details/13.md) |
| 14 | Social Network Integration                  | Social Network-Based Filtering                     |                                | [Details](./details/14.md) |


