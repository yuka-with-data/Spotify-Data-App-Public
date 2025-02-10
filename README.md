# [Deprecated] Spotify Track Data Exploration & Visualization App

Note: This project is deprecated due to changes in the behavior of the Spotify Web API.

This application offers a dynamic and engaging way to explore and analyze the musical qualities of Spotify's latest hit chart playlists, alongside a comparison with your personal favorite tracks. Powered by Streamlit, this tool not only showcases data visualizations of key track attributes but also provides insightful analytics to deepen your understanding of current musical trends. Whether you're a music enthusiast or an industry analyst, this application brings the world of Spotify's streaming data to your fingertips, offering a unique perspective on what makes a song popular in today's ever-evolving music landscape.

## Motivation:

Originally inspired by the discovery of talented musicians from non-English-speaking regions, this Spotify app began as an exploration into the potential of these artists to break into global mainstream music charts. My initial project analyzed how well the musical attributes of these artists matched up with the top 50 most streamed songs on Spotify in 2023, aiming to uncover whether these artists could resonate globally given their alignment with current music trends.

From this foundational work, the project has expanded into a multi-page application that offers comprehensive musical analysis. This platform not only tells the evolving data stories of the music scene but also dissects these analyses from various angles. As users engage with the data, they can enjoy listening to the music through an embedded player, enhancing the interactive experience. This expansion aims to deepen the understanding of music trends, celebrate diverse musical talents, and provide rich, actionable insights for music enthusiasts.

## Analysis
- Top Chart Analysis: Delve into Spotify's latest hit charts and uncover the attributes that contribute to the success of these tracks. Visualize trends and compare key metrics across genres and artists.
- Track Recommendation: Discover new music tailored to your taste. Our recommendation engine analyzes your preferences to suggest tracks that resonate with your musical style.
- Popularity Check: Gauge the popularity of any track or artist. Understand the metrics that influence Spotify's popularity scores and see how your favorite music stacks up.
- Track Comparison: Conduct a side-by-side comparison of tracks. Analyze and visualize differences in musical attributes such as tempo, energy, valence, and more.
- Era Comparison: Journey through different music eras. Compare and contrast the evolving characteristics of music across decades, from the rhythms of the '70s to the beats of today.
- Fine-Tuned Recommendation Tracks: Experience personalized music discovery like never before. Set your own criteria or use pre-defined profiles to explore music that fits your exact taste profile. See your recommendations come to life with interactive charts and listen directly from our platform.

## Target Users
1. Music Producers and Artists:
- Individuals interested in exploring the attributes of tracks that have found success in the mainstream music scene, purely for informational purposes.
- Those looking for insights into the musical characteristics that might contribute to a song's popularity, understanding that these insights are exploratory and not prescriptive.
2. A&R Representatives:
- A&R professionals curious about identifying talent whose style may currently align with trends observed in popular music charts, with the caveat that this analysis serves as an additional information source and not a decision-making tool.
- Representatives seeking to augment their talent scouting with data-driven insights into musical trends, acknowledging the informational nature of such analysis.
3. Data Analysis in the Music Industry:
- Professionals engaged in the analysis of music industry trends, seeking to incorporate data-driven insights into their decision-making process, with an understanding that these insights are for informational purposes only.
4. Music Enthusiasts and Researchers:
- Researchers and enthusiasts exploring the dynamics behind popular music trends, with an interest in understanding what contributes to a song's success on a purely informational basis.
- Individuals with a keen interest in music analysis, looking to satisfy their curiosity about the attributes of successful tracks without the expectation of professional guidance.

## Key Features:
- Attribute Comparison: Dive into the danceability, valence, energy, acousticness, instrumentalness, liveness, and speechiness percentages of the top 100 songs, and compare them with your selected track.

- Interactive Radar Chart: Visualize attribute comparisons through an interactive radar chart that dynamically updates based on user input. The radar chart provides an intuitive representation of various audio features, such as danceability, valence, energy, acousticness, instrumentalness, liveness, and speechiness. Users can input the artist and track, and the chart dynamically reflects the audio attribute values of the selected track compared to the average values of the top tracks from the specified year.

- Tempo Historgram: Explore the distribution of tempos among the top tracks and compare them to the tempo of your selected track. The histogram chart displays the frequency of different tempo ranges, allowing users to understand the tempo characteristics of their chosen track in the context of the broader music landscape.

- Key Distribution: Examine the distribution of musical keys among the top tracks. The bar chart visually represents the frequency of each musical key, enabling users to observe the prevalence of specific keys in popular songs. Additionally, the user's selected track is highlighted, providing insight into the key of the chosen song relative to the top tracks.

- Duration Histogram Chart: Investigate the duration distribution of top tracks and compare it to the duration of your chosen track. The histogram chart illustrates the frequency of different track durations, allowing users to grasp the typical length of popular songs. The chart also features a vertical line indicating the duration of the selected track, providing a clear reference point for comparison.

- Loudness Histogram Chart: Delve into the loudness trends of top tracks with the loudness histogram chart, showcasing the distribution of loudness levels in decibels (dB). Highlighting the loudness of your chosen track with a vertical marker, this chart offers a straightforward comparison against popular songs. It serves as an intuitive tool to gauge how the selected track's volume aligns with the prevailing music industry standards, enriching your understanding of its sonic attributes in the context of current hits.

- Explicitness Pie Chart: Explore the explicit content landscape among top tracks using the explicitness pie chart. This chart segments songs into explicit and non-explicit categories, providing a visual breakdown of content nature. When your selected track's explicit status matches one of the categories, that slice is subtly exploded outwards to draw attention. This feature not only highlights the explicitness status of your track but also offers insights into the balance between explicit and clean content in popular music, offering a unique perspective on content trends in the industry.

- Genres Word Cloud: Discover the diversity of musical genres represented among the top tracks with a visually striking word cloud. This feature aggregates genre data from the selected playlist, presenting it in a word cloud where the size of each genre name correlates with its frequency. This allows users to quickly grasp the predominant music styles and genre influences of their chosen track. The word cloud offers a unique and visually engaging overview of the musical genre landscape. 

- Popularity Gauge Chart: Gain insights into the current popularity score of the selected track through a dynamic gauge chart. The chart visually represents the popularity score on a scale from 0 to 100, allowing users to assess the track's popularity relative to other songs. This feature provides a quick and engaging way to understand the current standing of the chosen track.

- Similar Track Recommendations: Discover tracks similar to your selection with Spotify's recommendation feature, which analyzes the musical qualities of your chosen track to suggest five others with a similar vibe or sound. This list is purely based on the track's characteristics, ensuring a focused exploration of new music.

## Usage:
Choose an analysis from the sidebar menu and let your musical data journey begin.

## Spotify's Official Hit Charts
Here are Spotify's official hit charts currently available for comparison, with the list continuously expanding.
- Billboard Hot 100 (Weekly Update)
- Top 50 Global (Daily Update)
- Top Songs Global (Weekly Update)
- Big On Internet

Attributes included:
1. Track Name: The title or name of the track.
2. Artist Name: The name of the artist or group associated with the track.
3. Is_explicit: Indicates whether a track contains explicit content, such as strong language or mature themes. Tracks are marked as either explicit (true) or not explicit (false).
4. Danceability: A measure of how suitable a track is for dancing, ranging from 0 (least danceable) to 1 (most danceable).
5. Valence: Describes the musical positiveness conveyed by a track, ranging from 0 (negative) to 1 (positive).
6. Energy: Represents the intensity and activity of a track, with values ranging from 0 (low energy) to 1 (high energy).
7. Acousticness: Indicates the likelihood of a track being acoustic, with values closer to 1 representing higher acoustic qualities.
8. Instrumentalness: Reflects the likelihood of a track being instrumental, with values closer to 1 suggesting a higher degree of instrumentals.
9. Liveness: Measures the probability that a track was performed live, ranging from 0 (studio recording) to 1 (live performance).
10. Speechiness: Indicates the presence of spoken words in a track, with values closer to 1 representing tracks with more speech-like elements.
11. Key: Represents the musical key of the track, encoded as integers ranging from 0 to 11.
12. Tempo: Denotes the speed or pace of a track, measured in beats per minute (BPM).
13. Loudness: Measures the overall average loudness of a track in decibels (dB). Values typically range between -60 dB and 0 dB. Higher values indicate louder tracks. 
14. Popularity: A numerical score indicating the popularity of a track, with higher values signifying greater popularity.
15. genres: A compilation of music genres associated with the track's artist, reflecting the artist's overall music style and influences. Genres are derived from the artist's body of work rather than individual tracks or albums, providing insight into the broader stylistic contexts the artist operates within. 
16. Duration (ms): The duration of the track in milliseconds.
17. ID: A unique identifier assigned to each track, facilitating easy retrieval and reference.

## Note:
This application is currently under active development and is not ready for deployment at this stage. New features and functionalities are being actively explored and integrated to provide a more comprehensive music analysis and recommendation platform.

## Privacy:
This app does not log personal information or user activity. All analyses are conducted in real-time using publicly available Spotify data.

## Acknowledgements:
- Streamlit, for providing the framework that powers our app.
- The Spotify Web API, for the rich dataset that fuels our analyses.

## Disclaimer:
This application is designed for educational and entertainment purposes only. The data used in this app is sourced from public APIs and may not be entirely accurate or up-to-date. The analysis and visualizations provided should not be considered professional advice, and the creator of this app is not responsible for any decisions made based on the information provided. Please note that this app is not affiliated with Spotify or any other third-party services. Use this app responsibly and be aware of the terms and conditions of the Spotify API. Enjoy exploring the data responsibly!
