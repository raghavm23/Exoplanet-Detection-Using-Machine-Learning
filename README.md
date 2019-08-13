# Exoplanet-Detection-Using-Machine-Learning

Exoplanets are defined as planets orbiting a star outside our solar system. NASA launched the Kepler satellite in 2009 with the mission to hunt exoplanets. The data gathered by the satellite have been made publicly available by NASA in an attempt to increase development in the field of astroinformatics, a cross-disciplinary field consisting of astronomy, data science and informatics. 

## *Paper Synopsis*
In this paper, various deep learning techniques to detect exoplanets using the intensity of light captured by Kepler space telescope have been explored. The dimming in flux (light intensity) of the stars indicates an orbiting body around that star. Preliminary analysis is performed and the data is prepared to be fed in to the data mining models. Multiple models have been used to efficiently classify the exoplanets. The first model, H2O’s Deep Learning, is based on a multi-layer feedforward artificial neural network. Then a Convolutional Neural Network, a Black Box method, is deployed to classify the exoplanets.  Finally, Gradient Boosting technique is performed using the XGBoost algorithm, an ensemble technique that works on the concept of Decision Tree and Bootstrap Aggregation. This paper will provide the results, model performance and efficiency of the various algorithms used to detect such exoplanets.

## *Dataset*
The dataset for the research is open-sourced, made publicly available by NASA. The data has a total of 5657 records and 3197 flux values which are numeric in nature. The dependent variable is a categorical variable – whether a star has a confirmed exoplanet or not.
