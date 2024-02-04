# **EmoChildMex: SER over Mexican Spanish**

![](/assets/tem.png)

## Description
EmoChildMex represents a groundbreaking initiative aimed at advancing the understanding and recognition of emotional expressions in Mexican Spanish, with a particular focus on children's speech. This project introduces TriEmoMex, a comprehensive database that amalgamates three distinct databases to create a unified resource tailored to the nuances of Mexican Spanish in a child demographic.

## Database
TriEmoMex is a novel database that integrates three pre-existing databases. This integration aims to enrich the data available for research and application in emotion recognition technologies.

**Databases used:**
* **Mexican Emotional Speech Database (MESD)** 
* **IESC-Child-2: Emotional Children's Speech for Personality Assessment Corpus** *The data base is a propiertary of the Centro de Investigación Científica y de Educación Superior de Ensenada, Baja California, "CICESE"*
* **EmoWisconsin Database**. *The Emowisconsin Data Base is a property of the Instituto Nacional de Astrofíscia, Óptica y Electrónica - CONCACYT, México*.

**Emotions:**
* Neutral
* Sadness
* Anger
* Surprise
* Fear
* Happiness
* Disgust
* None

![Distribution of labels with augmented data](/assets/data.png)

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
I welcome contributions from researchers, developers, and practitioners across disciplines interested in emotion recognition, linguistics, and child psychology. Potential areas for contributions include:

* **Model Enhancement**: Innovations in Deep Learning models that could further improve emotion recognition accuracy.
* **Database Expansion**: Contributions to the TriEmoMex database, whether through the addition of new samples, refinement of existing data, or the integration of new databases.
* *+Application Development**: Development of practical applications that leverage our research findings to benefit children and stakeholders in educational or psychological settings.

Contributors are encouraged to fork the repository, propose changes via pull requests, and participate in discussions to drive the project forward.

## License

*We like to thank to Duville, Alonso-Valerdi and Ibarra-zarate for their dedication of the collection of the Mexican Emotional Speech Database*
*Duville, M.M.; Alonso-Valerdi, L.M.; Ibarra-Zarate, D.I. Mexican Emotional Speech Database Based on Semantic, Frequency, Familiarity, Concreteness, and Cultural Shaping of Affective Prosody. Data 2021, 6, 130.*

*We like to thank CICESE for their dedication of the collection of IESC-Child-2 Corpus.* 
*Pérez-Espinosa, H., Gutiérres-Serafín, B., Martínez-miranda, J., & Espinosa-Curiel, I. E. (2022). Automatic children's personality assessment from emotional speech. Expert Systems with Applications, 187, 115885*

*We like to thank Dr. Humberto Pérez-Espinosa, Dr. Carlos A. ReyesGarcia, and Dr. Luis Villaseñor-Pineda, for their dedication of the collection of the Emowisconsin data base.*
*Pérez-Espinosa, Humberto, Carlos Alberto ReyesGarcía, and Luis Villaseñor-Pineda. "Emowisconsin: an emotional children speech database in mexican spanish." In Affective Computing and Intelligent Interaction, pp. 62-71. Springer Berlin Heidelberg, 2011. ISSN 0302-9743.*
