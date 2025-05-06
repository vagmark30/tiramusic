# Tiramusic
## Finding new music that you like is the best feeling according some people. Tiramisu is the best according to the same people. We combine that.

## Overview

Music discovery gamified. Users can suggest songs with each other. If the other person likes the song that you suggested (calculated depending on the playbacks?) you get points. The less famous the song-artist is, the more points you get. it can use the spotify api to create list and use that under the hood.

### Proposed Gameplay loop

Two players sign-up for the application, which creates a playlist on their behalf.

![](./plantumls/gameplay_loop.png)

1. Player A searches for a track to add to players B's list.
2. Player B is made aware of a new track being suggested by player A
3. Tiramusic then periodically checks Player B's recently played songs. If any of those songs played match those suggested by Player A, Player A is rewarded points.

**Scoring is adjust by the following factors:**

- Popularity of the band.
- Play count of the chosen track.
- Frequency of repeated plays.

**Possible points/achievements ideas:**

- Engagement related, streaks of suggesting music (x number of days).
- Mastering particular genres.
- Discovery of the most obscure artists/songs of the week.

## Motivations

1. **Discovery fatigue**: Overwhelmed by the vast number of music streaming services, playlists, and algorithms that curate music for them. The app could help alleviate this by making the discovery
process more fun and interactive.
1. **Personalization**: 
2. **Community engagement**: A gamified app could foster a sense of community among users. Imagine users competing with each other to discover new music, share recommendations, or participate in music-related challenges.
3. **Discovery metrics**: Incentivize users to continue exploring.
   - various metrics to measure user progress
   - total points
   - total points on genres( Reggea master, etc)
   - total points on artists

## Some potential features you might consider:

1. **Explore mode**: Offer a mode where users can browse through various curated playlists or radio stations with hints and clues about the featured tracks. base on https://www.music-map.com/ and https://www.gnoosic.com/
2. **Bounty**: Users propose a theme/mood/scenario - users propose songs to match. Winner determined by vote/engagement by others.
3. **Anonymous Recommendation**: Users's could suggest music to others based on limited information regarding their listening habits. Player A really enjoys high tempo sad music - Player B must work within these confines & has no personal connection.

To be discussed:

1. **Target audience**: People who are done with the spotify algorithm.
2. **Competitor analysis**: Reddit? Instagram accounts? Vague and not personalized.
3. **Monetization strategy**: New music in our ears is already enough.
4. **Technical requirements**: What kind of infrastructure and resources will be needed to build and maintain the app? BE Java(Thomas Babs ++), FE Angular SPA (Back-end lads who want to learn frontend) ?
