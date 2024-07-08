# Recommendation Systems for Streaming Platforms

Storytelling has always been at the core of human nature. Major technological breakthroughs that changed society in fundamental ways have also allowed for richer and more engaging stories to be told. It is not hard to imagine our ancestors gathering around a fire in a cave and enjoying stories that were made richer by supporting cave paintings. Writing, and later the printing press, led to more varied and richer stories that were distributed more widely than ever before. More recently, television led to an explosion in the use and distribution of video for storytelling. Today, all of us are lucky to be witnessing the changes brought about by the Internet. Like previous major technological breakthroughs, the Internet is also having a profound impact on storytelling.

OTT streaming platforms lie at the intersection of the Internet and storytelling. This is the **era of Internet television**. In December of 2015, consumer research from Netflix estimated that a subscriber loses interest after 60 to 90 seconds of browsing before they choose something or abandon the streaming platform. This is where algorithms step in. Let's understand and analyze the **Recommendation systems** used in streaming platforms which is the key pillar of this infrastructure. 

## Introduction

As streaming platforms have emerged as leading sources for entertainment media — particularly for film, television, music — access to content has increased to an overwhelming amount.

Actor Marc Maron theorizes that everyone had one person in their life that influenced their interests by introducing them to new films, music, books, clothes, or anything else. This person came to us at an influential time and changed the trajectory of our lives. That role is now being filled by algorithms.

- Amazon has been using recommendations from algorithms for its service since 1998.
- Netflix has been using algorithms for recommending entertainment since 2007 when it was only sending DVDs.

Now, all streaming platforms use their algorithms alongside machine learning to guide the consumer to decide what to watch. They aim for:
- Increasing number of Subscribers
- Increasing viewing Hours
- Reducing Churn rate (Cancellation of service within threshold time)

The recommendation systems can be broadly categorized into:

1. **Content-Based:** Recommends using metadata [tags, text] of items similar to those the user has interacted with previously based on its attributes.
2. **Collaborative Filtering:** Recommends content based on the preferences and behaviors of other users with similar tastes or behavioral patterns.
3. **Knowledge-Based:** Recommends by correlating explicit knowledge about user preferences and item attributes using their similarities. (For discovery of new content)

## Market Case Study - NETFLIX

**Netflix** is one of the most transparent platforms when it comes to algorithms.

In 2006 Netflix hosted a competition with a $1 million prize for a recommender system that was better than its current system. One team was able to create such a system, it’s not clear if Netflix implemented it.

In 2007, Netflix pivoted from its original DVD delivery model to streaming, changing its entire system of recommendations. 

In 2014 Netflix invested 3% of its revenue to develop a recommendation engine that eventually included data from all countries and could be altered in real time. 

In 2015, Netflix stated that choices made based on the recommender system account for around 80% of the hours streamed and the other 20% are the result of searches that utilize an entirely different set of algorithms. 

For its algorithm, Netflix uses data on what users watch, what they search, how they rate, when they watch, and more to customize page construction, genre rows, trending videos, order of videos, and even the icons. Netflix claims that these systems have decreased its churn by several percentage points and have saved $1 billion per year. 

One of the things that makes Netflix’s page layout so interesting is its very unique genre titles such as “Reluctant Adults” or “Gritty Movies” which Netflix calls “altgenres.” According to an article by The Atlantic, in 2014, Netflix had nearly 77,000 altgenres which were created through a combination of machine learning and human intellect and are part of how Netflix tailors its recommendations through algorithms. 

Netflix has published much of the details on its algorithms. The first use of algorithm series is in the matrix-like layout and content of each user’s homepage:

- **Personalized Video Ranker (PVR):** Takes the catalog of videos and orders them for each member within the genre rows.
- **Top-N Video Ranker:** Generates recommendations for the Top Picks row, personalizing the selection for a member.
- **Trending Now:** Similar to Top-N in that it focuses on trends, but this one particularly focuses on short-term trends like Valentine’s Day or a weather event while still including consideration of personalization.
- **Continue Watching:** Sorts recently viewed content using an estimate of what a user is most likely to continue watching or re-watch.
- **Video-Video Similarity (Because You Watched):** Develops recommendations based on a piece of content the user interacted with. These recommendations are not personalized, but the titles that the Because You Watched features are personalized depending on estimations of a user’s preference for content.
- **Evidence Algorithm:** Helps users decide if the content they have clicked on is what they want. These metrics include predicted star rating, the information on the content, and the icons shown for content in rows. Examples for this include whether to show if the content has won an award or which icon the user will most likely choose.
- **Search Algorithm:** Made up of multiple algorithms that help determine which results are most relevant for a user by including partial queries (“frie” showing “friend”) or concepts (showing French movies for “French” instead of titles including “French”).
- **Page Generation Algorithm:** Uses all of the algorithms above to personalize which rows show up and in what order.

  ![Netflix](./Algorithms1.jpg)

## Use Cases

I have identified some Business Use-cases that are significant in this domain and tried to brief each use case with its [understanding, challenges, primary algorithm used, complexity analysis, examplary code]

| #  | Use Case                                    | Algorithm                                          | Code |
|----|---------------------------------------------|----------------------------------------------------|------|
| 1  | [Personalized Recommendation](./details/1.md) | Collaborative Filtering                            | [View](https://github.com/gorse-io/gorse) |
| 2  | [Genre-based Suggestions](./details/2.md)     | Content-Based Filtering                            | [View](https://github.com/vjvishaljha/Recommender_Sys) |
| 3  | [New Release Recommendation](./details/3.md)  | Knowledge Graph Attention Network                  | [View](https://github.com/xiangwang1223/knowledge_graph_attention_network) |
| 4  | [Trending Content Discovery](./details/4.md)  | Popularity-Based Filtering                         | [View](https://github.com/convenience-tinashe-chibatamoto/Movie-Recommendation-System) |
| 5  | [Seasonal Content Suggestion](./details/5.md) | Time-Based Filtering                               | [View](https://github.com/chen0040/mxnet-recommender) |
| 6  | [User Engagement Optimization](./details/6.md)| Reinforcement Learning                             |                     |
| 7  | [Multi-Modal Content Recommendation](./details/7.md) | Multi-Modal Recommender Systems             | [View](https://github.com/enoche/MultimodalRecSys) |
| 8  | [Geo-Specific Recommendation](./details/8.md) | Geo-Based Filtering                                | [View](https://github.com/ustcml/GeoSAN) |
| 9  | [Personal Playlist Curation](./details/9.md)  | Sequential Recommendation                          | [View](https://github.com/SamU65/Celluloid-playlist-generator) |
| 10 | [User Retention/Churn Reduction](./details/10.md) | Random Forests + Logistic Regression           | [View](https://github.com/rohitharitash/CustomerChurnReduction) |
| 11 | [Real-Time Content Updates and Notifications](./details/11.md) | Stream-based Collaborative Filtering   | [View](https://github.com/BaseMax/real-time-notifications-nats-go) |
| 12 | [User-Specific Advertisement Recommendation](./details/12.md) | Context-Aware Recommender Systems   | [View](https://github.com/rishikonapure/Advertisement-Recommendation) |
| 13 | [Diverse Content Exploration](./details/13.md) | Diversity-Aware Recommender Systems                | [View](https://github.com/guanghuixu/AnchorCaptioner) |
| 14 | [Social Network Integration](./details/14.md)  | Social Network-Based Filtering                     | [View](https://github.com/reddyprasade/Deep-Learning) |





### Code References (Github)

1. Gorse - An open-source recommender system engine. [GitHub Repository](https://github.com/gorse-io/gorse)
2. Recommender Sys - Content-Based and Hybrid Recommender System. [GitHub Repository](https://github.com/vjvishaljha/Recommender_Sys)
3. Knowledge Graph Attention Network (KGAT) - Knowledge Graph Attention Network for Recommendation. [GitHub Repository](https://github.com/xiangwang1223/knowledge_graph_attention_network)
4. Movie Recommendation System - Popularity-Based Filtering. [GitHub Repository](https://github.com/convenience-tinashe-chibatamoto/Movie-Recommendation-System)
5. MXNet Recommender - Time-Based Filtering. [GitHub Repository](https://github.com/chen0040/mxnet-recommender)
6. LangChain - User Engagement Optimization with Reinforcement Learning. [GitHub Repository](https://github.com/hwchase17/langchain)
7. MultimodalRecSys - Multi-Modal Recommender Systems. [GitHub Repository](https://github.com/enoche/MultimodalRecSys)
8. GeoSAN - Geo-Based Filtering. [GitHub Repository](https://github.com/ustcml/GeoSAN)
9. Celluloid Playlist Generator - Sequential Recommendation. [GitHub Repository](https://github.com/SamU65/Celluloid-playlist-generator)
10. Customer Churn Reduction - Random Forests + Logistic Regression. [GitHub Repository](https://github.com/rohitharitash/CustomerChurnReduction)
11. Real-Time Notifications - Stream-Based Collaborative Filtering. [GitHub Repository](https://github.com/BaseMax/real-time-notifications-nats-go)
12. Advertisement Recommendation - Context-Aware Recommender Systems. [GitHub Repository](https://github.com/rishikonapure/Advertisement-Recommendation)
13. Anchor Captioner - Diversity-Aware Recommender Systems. [GitHub Repository](https://github.com/guanghuixu/AnchorCaptioner)
14. Deep Learning - Social Network-Based Filtering. [GitHub Repository](https://github.com/reddyprasade/Deep-Learning)

### Additional Resources

1. Next TV. [Website](https://nexttv.github.io/)
2. CleverTap - OTT. [Blog](https://clevertap.com/blog/ott/)
3. Dacast. [Website](https://www.dacast.com/)
4. Gomez-Uribe, C. A., & Hunt, N. The Netflix Recommender System: Algorithms, Business Value, and Innovation.
5. AMT Lab - Algorithms in Streaming Services. [Blog](https://amt-lab.org/blog/2021/8/algorithms-in-streaming-services)
6. Streaming Media. [Website](https://www.streamingmedia.com/)
7. Adalian, J. (2020, July 17). One Thing Peacock Does Well? 'Live' Channels. [Article](https://www.vulture.com/2020/07/peacock-live-channels-review.html)
8. Alexander, J. (2020, May 27). HBO Max is taking on Netflix with human curation instead of solely relying on algorithms. [Article](https://www.theverge.com/21268972/hbo-max-design-recommendation-human-curation-friends-kids-proﬁles)
9. Alvino, C., & Basilico, J. (2015, April 9). Learning a Personalized Homepage. [Article](https://netflixtechblog.com/learning-a-personalized-homepage-aa8ec670359a)
10. DeAngelis, F. S. (2015, August 07). Artiﬁcial intelligence: How algorithms make systems smart. [Article](https://www.wired.com/insights/2014/09/artiﬁcial-intelligence-algorithms-2/)
11. Jordan, J. (2019, November 19). "The creativity code": Is AI taking over Creative Industries? [Review](https://amt-lab.org/reviews/2019/11/the-creativity-code-is-ai-taking-over-creative-industries?rq=sautoy)

