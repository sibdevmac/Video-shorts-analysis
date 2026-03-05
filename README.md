# TikTok vs YouTube Shorts: Are Short Videos Replacing Search Engines?

## Project Overview

While watching a video on YouTube, the creator mentioned an interesting idea:  
many people today are increasingly using **TikTok as an alternative search engine**.

Instead of searching on traditional platforms like Google, users are searching directly on TikTok for topics such as:

- travel tips
- cooking tutorials
- product reviews
- life hacks

Although this shift may appear harmless, it raises important concerns.  
Social media platforms may expose users to **biased information, misinformation, or propaganda**, especially when content is driven by algorithms rather than verified sources.

Therefore, this project analyzes whether **short-form video platforms are beginning to replace traditional search engines for information discovery**.

---

## Dataset

Dataset Source:

https://huggingface.co/datasets/tarekmasryo/youtube-tiktok-trends-dataset-2025/tree/main/data

The dataset contains trending content data from:

- TikTok
- YouTube Shorts

### Key Columns

- platform
- country
- region
- category
- hashtag
- views
- likes
- comments
- shares
- saves
- engagement_rate
- completion_rate
- duration_sec

These variables allow the study of **engagement behavior, information discovery, and viewing patterns**.

---

## Methodology

The analysis was conducted using **Python data analysis tools**, including:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

The following analytical approaches were used:

- Engagement comparison
- Hashtag discovery analysis
- Watch behavior comparison
- Search replacement scoring
- Statistical hypothesis testing (T-test)

The main objective was to evaluate whether **short-form videos behave similarly to search engines in information discovery**.

---

## Key Findings

### 1. Higher Engagement on TikTok

The analysis revealed that **TikTok videos generally receive more views compared to YouTube Shorts**.

Additionally, TikTok content shows higher levels of:

- saves
- shares
- comments

This indicates that TikTok functions as a **social-networked search environment**, where users not only discover information but also interact and discuss it.

However, the open and highly expressive nature of TikTok may also create **skepticism or emotional stress among viewers**, especially when controversial topics spread quickly.

The **Engagement Comparison graph** confirmed that TikTok generates **higher total engagement** than YouTube Shorts.

---

### 2. Hashtags Drive Information Discovery

Another key observation was the role of hashtags in creating trends and spreading information.

The **Top Discovery Topics analysis** showed that the hashtag: #FWP appears frequently among trending topics.

This suggests that discovery on TikTok is highly **personalized and algorithm-driven**.

However, such personalization can lead to **biased content exposure**, which may increase the risk of **disinformation campaigns influencing news consumption**.

---

### 3. Shorter Attention Span

The **Watch Behavior Comparison graph** showed that TikTok users tend to consume shorter content compared to YouTube viewers.

This suggests that TikTok encourages a **shorter attention span**.

A reduced attention span may limit **critical analysis of information**, which could lead users to form opinions based on brief or incomplete information.

Such patterns could potentially shape **biased perceptions when consuming news or informational content**.

---

### 4. Search Replacement Score

To measure whether TikTok could function as a **search engine alternative**, a custom metric called the **search_replacement_score** was created.

This score combines engagement indicators such as:

- engagement rate
- completion rate
- save rate

Results:

| Platform | Search Replacement Score |
|----------|--------------------------|
| TikTok   | 0.77 |
| YouTube  | 0.62 |

The higher score for TikTok suggests a **greater potential for TikTok to function as an alternative to conventional search engines**.

To validate this difference statistically, a **T-test** was performed.

Results:
T-statistic = 150.36
P-value < 0.001


This extremely significant result indicates that **engagement behavior differs strongly between TikTok and YouTube Shorts**.

The finding suggests that **short-form video platforms significantly influence modern information discovery patterns**.

---

### 5. Rapid Hashtag Trends

Further analysis showed that certain hashtags rise quickly in popularity on TikTok.

Common trending topics included:

- lifehacks
- sports
- food
- workout
- skincare

These topics often focus on **personal experiences and quick advice**, which may not always be supported by reliable sources.

This raises concerns about **content authenticity and information reliability** on social video platforms.

---

### 6. Global Spread of Social Search

The dataset also suggests that the use of TikTok as a **search alternative is spreading globally**.

However, the overall relevance score across regions was approximately: 0.33 which is not much but it could replace the search engines in the future.


This indicates that although TikTok shows increasing influence in information discovery, it **has not yet replaced traditional search engines globally**.

---

## Conclusion

This analysis suggests that **short-form video platforms, particularly TikTok, are increasingly shaping how users discover information online**.

Key insights include:

- TikTok generates higher engagement than YouTube Shorts.
- Hashtags and algorithms strongly influence information discovery.
- Shorter attention spans may affect critical evaluation of information.
- TikTok shows potential as a search alternative but has not yet replaced traditional search engines.

While TikTok may continue to grow as a **social search platform**, traditional search engines still play an essential role in **structured and verified information retrieval**.

---

## Author

Sibankar Saha
