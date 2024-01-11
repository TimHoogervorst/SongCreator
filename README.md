# SongCreator

Project: Song Recommendation System Using Clustering

Objective: The objective of this project is to develop a song recommendation system using clustering techniques. The system will take a user-provided song as input and recommend other songs from the same cluster. The recommendation will be based on the audio features of the songs.

Workflow:

The system will follow the following workflow:

User inputs a song: The user will provide a song name or URL.

Get user's song audio features: The system will extract the audio features of the user's song. These features can be extracted using various tools, such as librosa.

Predict user's song cluster membership: The system will use a clustering algorithm to predict the cluster membership of the user's song. This will be done by comparing the audio features of the user's song to the audio features of songs in the training data.

Recommend another song from the same cluster: The system will recommend another song from the same cluster as the user's song. If the user's song is in the hot songs database, the system will recommend a song from the hot songs database. Otherwise, it will recommend a song from the not hot songs database.

Repeat: The system will continue to recommend songs until the user indicates that they do not want any more recommendations.
