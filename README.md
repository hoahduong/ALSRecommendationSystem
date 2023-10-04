# DSGA1004 - BIG DATA
## Final project

# Overview

In the final project, you will apply the tools you have learned in this class to solve a realistic, large-scale applied problem.
Specifically, you will build and evaluate a collaborative-filter based recommender system. 

In either case, you are encouraged to work in **groups of up to 3 students**:

- Groups of 1--2 will need to implement one extension (described below) over the baseline project for full credit.
- Groups of 3 will need to implement two extensions for full credit.

## The data set

In this project, we'll use the [ListenBrainz](https://listenbrainz.org/) dataset, which we have prepared for you in Dataproc's HDFS at `/user/bm106_nyu_edu/1004-project-2023/`.  A copy is also available on the Greene cluster at `/scratch/work/courses/DSGA1004-2021/listenbrainz/`.

This data consists of *implicit feedback* from music listening behavior, spanning several thousand users and tens of millions of songs.
Each observation consists of a single interaction between a user and a song.
**Note**: this is real data.  It may contain offensive language (e.g. in song titles or artist names).  It is entirely possible to complete the assignment using only the interaction data and ID fields without investigating metadata.
