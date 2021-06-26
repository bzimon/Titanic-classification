# Titanic - Who is going to survive ? - classification

Greetings welcome to my Titanic projects in which I am going to make a classifier which can tell us who was most likely to survive on Titanic !
With my classifier if you could turn back the time, you would be able to warn the least likely to survive and save them from disaster.

If you are interested in my methodology, feel free to go step by step or cell by cell 😉 through the notebook.
For final results and conclusions go to the Kaggle submission section at the end of the notebook.

Explanation of each column in the dataframe can be found here https://www.kaggle.com/c/titanic/data

<h1>Table of Contents<span class="tocSkip"></span></h1>
<div class="toc"><ul class="toc-item"><li><span><a href="#Titanic---Who-is-going-to-survive-?---classification" data-toc-modified-id="Titanic---Who-is-going-to-survive-?---classification-1"><span class="toc-item-num">1&nbsp;&nbsp;</span>Titanic - Who is going to survive ? - classification</a></span></li><li><span><a href="#Imports" data-toc-modified-id="Imports-2"><span class="toc-item-num">2&nbsp;&nbsp;</span>Imports</a></span></li><li><span><a href="#Functions" data-toc-modified-id="Functions-3"><span class="toc-item-num">3&nbsp;&nbsp;</span>Functions</a></span></li><li><span><a href="#Innitial-accuracy" data-toc-modified-id="Innitial-accuracy-4"><span class="toc-item-num">4&nbsp;&nbsp;</span>Innitial accuracy</a></span></li><li><span><a href="#Feature-Engineering" data-toc-modified-id="Feature-Engineering-5"><span class="toc-item-num">5&nbsp;&nbsp;</span>Feature Engineering</a></span><ul class="toc-item"><li><span><a href="#Embarked,-Sex,-Name_len" data-toc-modified-id="Embarked,-Sex,-Name_len-5.1"><span class="toc-item-num">5.1&nbsp;&nbsp;</span>Embarked, Sex, Name_len</a></span></li><li><span><a href="#Coorelation" data-toc-modified-id="Coorelation-5.2"><span class="toc-item-num">5.2&nbsp;&nbsp;</span>Coorelation</a></span></li><li><span><a href="#Title" data-toc-modified-id="Title-5.3"><span class="toc-item-num">5.3&nbsp;&nbsp;</span>Title</a></span></li><li><span><a href="#Family" data-toc-modified-id="Family-5.4"><span class="toc-item-num">5.4&nbsp;&nbsp;</span>Family</a></span></li><li><span><a href="#Age-groups" data-toc-modified-id="Age-groups-5.5"><span class="toc-item-num">5.5&nbsp;&nbsp;</span>Age groups</a></span></li><li><span><a href="#Ensemble-of-models" data-toc-modified-id="Ensemble-of-models-5.6"><span class="toc-item-num">5.6&nbsp;&nbsp;</span>Ensemble of models</a></span></li></ul></li><li><span><a href="#Hyperparameters-tuning" data-toc-modified-id="Hyperparameters-tuning-6"><span class="toc-item-num">6&nbsp;&nbsp;</span>Hyperparameters tuning</a></span></li><li><span><a href="#Kaggle-submission" data-toc-modified-id="Kaggle-submission-7"><span class="toc-item-num">7&nbsp;&nbsp;</span>Kaggle submission</a></span></li></ul></div>
