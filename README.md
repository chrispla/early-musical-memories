# Early Musical Memories

Course project for **Music Perception and Cognition**, Sound and Music Computing Master's 2021-2022, Universitat Pompeu Fabra

<img title="" src="https://github.com/chrispla/early-musical-memories/blob/main/first-musical-memory-wordcloud.png" alt="Wordcloud with most common words people associate their early musical memories with. Some of the most prominent are playing, singing, CD, saxophone, and cartoons." width="400" data-align="center">

### Motivation

Different types of early memories have been associated with different types of emotional responses, such as, for example, **visual** memories generally being more **positive**, with **verbal** memories being more **negative**. There might even be an association between the type of memory and the **offset of infantile amnesia** (the inability of adults to retrieve memories from the first 2 to 4 years of their lives) [*]. These same associatations have not been extensively studied for memories that primarily involve a musical context. In this project, we set to find out more about the **moods**, **emotions**, and **vividness** people associate with their **earliest musical memories**. 

[*] Emotional trauma and childhood amnesia - Rhawn Joseph - Consciousness & Emotion, Volume 4, Issue 2, Jan 2003, p. 151 - 179; https://doi.org/10.1075/ce.4.2.02jos

### Methodology

We further separate the musical memories in the following categories:

* Lullabies

* Radio / CDs / Records

* TV cartoons / shows / movies

* Performance among relatives or friends

* Concert or musical events

* You playing an instrument

* Music class

For each category, we investigate the associated valence and vividness. We do this under various secondary variables, including the demographic- and music-experience-related variables below:

* Country of origin

* Gender

* Musician (Y/N)

* Musician relatives (Y/N)

* Radio/TV music in the household (Y/N)

* Records/CDs in the household (Y/N)

* Someone performing in the household (Y/N)

* Positivity of music experience (5-point scale)

* Positivity of childhood overall (5-point scale)

Some questions that ask for a descriptive answer are also present in the form responses, but not currently included in this analysis.

### Running

The `responses.csv` file contains the responses to the survey as rows, with the questions as the file header. Some cleaning and visualizations are provided in the `visualizations.ipynb` notebook. It's recommended to run this notebook in a python 3.8+ environment using the module versions in `requirements.txt`. 
