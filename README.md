## Movie similarities analysis by plot

The idea is to associate movies just by the plots and find similarities using **NLP** and **clustering**. The dataset has the top 100 movies from IMDb with the plots of Wikipedia and IMDb. 

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

---

### Requirements

`python3` `jupyter notebook` 

### Dependencies

`pandas` `numpy` `nltk` `re` `Scikit-learn` `matplotlib` `SciPy`

---

### About

Most of the times the movies are related by features such as gender, director, year, country of orign among others. Other type of relation widley use by prediction algorithms is the similarities between users. But in this case I wanted to try if we can associate movies based upon the plots published in Wikipedia and IMDb. The project takes this plots and tokenize, stem, vectorize, cluster and plot them. 

### Conclusion

There are some obvious similarities such as both Godfather's movies, but there are some others such as Titanic with City Lights that we know are not alike. A next step would be to investigate these plots and match words to try to understand this situation, but it is not promising. Although the results are not acceptable was an experiment worht trying.

---

The dataset was published in Datacamp and was submitted by Anubhav Singh.

This notebook is based on [Anubhav Singh's Datacamp Project](https://www.datacamp.com/projects/648).
