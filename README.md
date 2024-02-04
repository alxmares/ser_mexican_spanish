# **EmoChildMEx: SER over Mexican Spanish**

## Description
EmoChildMex represents a groundbreaking initiative aimed at advancing the understanding and recognition of emotional expressions in Mexican Spanish, with a particular focus on children's speech. This project introduces TriEmoMex, a comprehensive database that amalgamates three distinct databases to create a unified resource tailored to the nuances of Mexican Spanish in a child demographic.

## Database
TriEmoMex is a novel database that integrates three pre-existing databases. This integration aims to enrich the data available for research and application in emotion recognition technologies.

**Databases used: **
* **Mexican Emotional Speech Database (MESD)** 
* **IESC-Child-2: Emotional Children's Speech for Personality Assessment Corpus** *The data base is a propiertary of the Centro de Investigación Científica y de Educación Superior de Ensenada, Baja California, "CICESE"*
* **EmoWisconsin Database**. *The Emowisconsin Data Base is a property of the Instituto Nacional de Astrofíscia, Óptica y Electrónica - CONCACYT, México*.

**Emotions: **
* Neutral
* Sadness
* Anger
* Surprise
* Fear
* Happiness
* Disgust
* None

## Deep Learning Created
Four CNN models were created and seigned with the objective of enhancing the accuracy and realibility of emotion detection across eight identified emotions.

* Simple CNN model
* CNN with LSTM
* CNN with Deeper Architecture
* Complex with Bidirectional LSTM

## Model Performance Comparison

The following table showcases the performance of the four Deep Learning models in terms of test accuracy and F1 score:

| Model    | Test Accuracy | Test F1 Score |
|----------|---------------|---------------|
| Model 1  | 45.38%        | 0.4511         |
| Model 2  | 35.60%        | 0.3253         |
| Model 3  | 41.85%        | 0.4069          |
| Model 4  | 43.48%        | 0.4341          |



## Contributing
We welcome contributions from researchers, developers, and practitioners across disciplines interested in emotion recognition, linguistics, and child psychology. Potential areas for contributions include:

* **Model Enhancement**: Innovations in Deep Learning models that could further improve emotion recognition accuracy.
* **Database Expansion**: Contributions to the TriEmoMex database, whether through the addition of new samples, refinement of existing data, or the integration of new databases.
* *+Application Development**: Development of practical applications that leverage our research findings to benefit children and stakeholders in educational or psychological settings.

Contributors are encouraged to fork the repository, propose changes via pull requests, and participate in discussions to drive the project forward.

## License
