# YouTube Recommendations and Effects on Sharing Across Online Social Platforms

## Paper

This repository includes replication material for [YouTube Recommendations and Effects on Sharing Across Online Social Platforms](https://arxiv.org/abs/2003.00970)

## Abstract

In January 2019, YouTube announced its platform would exclude potentially harmful content from video recommendations while allowing such videos to remain on the platform.
While this action is intended to reduce YouTube's role in propagating such content, continued availability of these videos via hyperlinks in other online spaces leaves an open question of whether such actions actually impact sharing of these videos in the broader information space.
This question is particularly important as other online platforms deploy similar suppressive actions that stop short of deletion despite limited understanding of such actions' impacts.
To assess this impact, we apply interrupted time series models to measure whether sharing of potentially harmful YouTube videos in Twitter and Reddit changed significantly in the eight months around YouTube's announcement.
We evaluate video sharing across three curated sets of anti-social content: a set of conspiracy videos that have been shown to experience reduced recommendations in YouTube, a larger set of videos posted by conspiracy-oriented channels, and a set of videos posted by alternative influence network (AIN) channels.
As a control, we also evaluate these effects on a dataset of videos from mainstream news channels.
Results show conspiracy-labeled and AIN videos that have evidence of YouTube's de-recommendation do experience a significant decreasing trend in sharing on both Twitter and Reddit.
At the same time, however, videos from conspiracy-oriented channels actually experience a significant increase in sharing on Reddit following YouTube's intervention, suggesting these actions may have unintended consequences in pushing less overtly harmful conspiratorial content.
Mainstream news sharing likewise sees increases in trend on both platforms, suggesting YouTube's suppression of particular content types has a targeted effect.
In summary, while this work finds evidence that reducing exposure to anti-social videos within YouTube potentially reduces sharing on other platforms, increases in the level of conspiracy-channel sharing raise concerns about how producers -- and consumers -- of harmful content are responding to YouTube's changes.
Transparency from YouTube and other platforms implementing similar strategies is needed to evaluate these effects further.

## Data and Code

The `data` directory currently includes time series data for the sharing of various collections of YouTube videos on Twitter and Reddit, grouped into:

- Videos published by channels identified as [Alternative Influence Network](https://datasociety.net/library/alternative-influence/) channels, 
- Videos identified as conspiracy-centric by [Faddoul et al.](https://farid.berkeley.edu/downloads/publications/arxiv20.pdf), 
- Videos by channels who have publish many conspiracy videos (i.e., conspiracy-oriented channels), and
- Mainstream-media videos.

The `notebooks` directory includes analysis of these video-sharing time series data, using interrupted time series models.

## Future Updates

In the near future, we will integrate the pipeline for generating these time series data from social media datasets.