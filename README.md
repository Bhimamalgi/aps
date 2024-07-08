# Recommendation Systems for Streaming Platforms

Storytelling has always been at the core of human nature. Major technological breakthroughs that changed society in fundamental ways have also allowed for richer and more engaging stories to be told. It is not hard to imagine our ancestors gathering around a fire in a cave and enjoying stories that were made richer by supporting cave paintings. Writing, and later the printing press, led to more varied and richer stories that were distributed more widely than ever before. More recently, television led to an explosion in the use and distribution of video for storytelling. Today, all of us are lucky to be witnessing the changes brought about by the Internet. Like previous major technological breakthroughs, the Internet is also having a profound impact on storytelling.
OTT streaming platforms lie at the intersection of the Internet and storytelling. This is the **era of Internet television**. In December of 2015, consumer research from Netflix estimated that a subscriber loses interest after 60 to 90 seconds of browsing before they choose something or abandon the streaming platform. This is where algorithms step in. Let's understand and analyze the **Recommendation systems** used in streaming platforms which is the key pillar of this infrastructure. 

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

I have identified some Business Use-cases that are significant in this domain and tried to brief each use case with its [understanding, challenges, primary algorithm used, complexity analysis, examplary code]

| #  | Use Case                                    | Algorithm                                          | Code |
|----|---------------------------------------------|----------------------------------------------------|------|
| 1  | [Personalized Recommendation](./details/1.md) | Collaborative Filtering                            | [View](https://github.com/gorse-io/gorse) |
| 2  | [Genre-based Suggestions](./details/2.md)     | Content-Based Filtering                            | [View](https://github.com/vjvishaljha/Recommender_Sys) |
| 3  | [New Release Recommendation](./details/3.md)  | Knowledge-Based Filtering                          | [View](https://github.com/xiangwang1223/knowledge_graph_attention_network) |
| 4  | [Trending Content Discovery](./details/4.md)  | Popularity-Based Filtering                         | [View](https://github.com/convenience-tinashe-chibatamoto/Movie-Recommendation-System) |
| 5  | [Seasonal Content Suggestion](./details/5.md) | Time-Based Filtering                               | [View](https://github.com/chen0040/mxnet-recommender) |
| 6  | [User Engagement Optimization](./details/6.md)| Reinforcement Learning                             |                     |
| 7  | [Multi-Modal Content Recommendation](./details/7.md) | Multi-Modal Recommender Systems             | [View](https://github.com/enoche/MultimodalRecSys) |
| 8  | [Geo-Specific Recommendation](./details/8.md) | Geo-Based Filtering                                | [View](https://github.com/ustcml/GeoSAN) |
| 9  | [Personal Playlist Curation](./details/9.md)  | Sequential Recommendation                          | [View](https://github.com/SamU65/Celluloid-playlist-generator) |
| 10 | [User Retention/Churn Reduction](./details/10.md) | Matrix Factorization with Side Information     | [View](https://github.com/rohitharitash/CustomerChurnReduction) |
| 11 | [Real-Time Content Updates and Notifications](./details/11.md) | Stream-based Collaborative Filtering   | [View](https://github.com/BaseMax/real-time-notifications-nats-go) |
| 12 | [User-Specific Advertisement Recommendation](./details/12.md) | Context-Aware Recommender Systems   | [View](https://github.com/rishikonapure/Advertisement-Recommendation) |
| 13 | [Diverse Content Exploration](./details/13.md) | Diversity-Aware Recommender Systems                | [View](https://github.com/guanghuixu/AnchorCaptioner) |
| 14 | [Social Network Integration](./details/14.md)  | Social Network-Based Filtering                     | [View](https://github.com/reddyprasade/Deep-Learning) |
