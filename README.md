This project explores users’ listening history to build a collaborative-filtering song recommendation system. First, a popularity model is built as a baseline using two methods of determining popularity. Then, a Latent Factor Model is built using the Alternating Least Square (ALS) algorithm provided in Spark’s library. Additionally, a single-machine approach using LightFM is implemented for comparison.

## The data set

In this project, we'll use the [ListenBrainz](https://listenbrainz.org/) dataset, which we have prepared for you in Dataproc's HDFS at `/user/bm106_nyu_edu/1004-project-2023/`.  A copy is also available on the Greene cluster at `/scratch/work/courses/DSGA1004-2021/listenbrainz/`.

This data consists of *implicit feedback* from music listening behavior, spanning several thousand users and tens of millions of songs.
Each observation consists of a single interaction between a user and a song.
**Note**: this is real data.  It may contain offensive language (e.g. in song titles or artist names).  It is entirely possible to complete the assignment using only the interaction data and ID fields without investigating metadata.
