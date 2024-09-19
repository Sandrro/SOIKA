Introduction
============
Sloyka documentation
Date: June, 2024 Version: 0.6
SLOYKA is a library aimed at enriching digital city models with data obtained from textual data of citizens' digital footprints, as well as at modeling vernacular assessment of urban environment quality.

Its main element is a constructible spatial semantic hypergraph, augmented by machine recognition of urban entities and locations.

The SLOYKA's final result is a spatial semantic hypergraph, which generates after two main stages: data receiving
(messages from the social network, mentioning particular city objects in them) and additional processes of data tagging of the collected data to obtain new columns in the resulting GeoDataFrame.
The resulting hypergraph can be used to predict events within existing urban objects (module :ref:`regional_activity`),
or to visualize already existing nodes and links and their further interpretation (module :ref:`graph_visualization`)

SLOYKA also provides methods for modeling social risks regarding the emotional evaluation of mentioned places.

Main features
--------------
* Social media parsing: getting posts, comments and replys
* City services and places extraction
* Emotion and text classifiers categorizing
* City's topic modelling
* Spatial-semantic graph building
* Regional activity evaluation

SLOYKA's Community chat:
https://t.me/sloyka_community