# MM1_2401FTDS_Unsupervised_Learning_Project
Building a collaborative and content-based recommender system for a collection of anime titles, capable of accurately predicting how a user will rate an anime title they have not yet viewed, based on their historical preferences.
![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white) [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](URL_TO_YOUR_APP)

<div id="main image" align="center">
  <img src="https://github.com/karabo/2401FTDS_Unsupervised_Learning/blob/main/anime.csv" width="550" height="300" alt=""/>
</div>

## Table of contents
* [1. introduction](#Introduction)
* [2. Project Goal](#ProjectGoal)
* [3. exploratory data analysis](#EDA)
* [4. models](#models)
* [5. streamlit](#streamlit)
* [6. conclusion and insights](#conclusionandinsights)
* [7. Team Members](#team-members)
  ## 1. Introduction <a class="anchor" id="introduction"></a>
In today's digital era, recommender systems play a crucial role in helping people find content that suits their interests. Platforms like Netflix, Amazon Prime, Showmax, and Disney rely on sophisticated algorithms to suggest movies and shows tailored to individual preferences. But have you ever wondered how these platforms seem to know your tastes so well?

This project aims to develop a recommender system specifically for anime titles, leveraging advanced machine learning techniques. The system will help anime fans discover new shows that match their unique preferences, making the viewing experience more enjoyable and personalized.



## 2. Project Goal <a class="anchor" id="Project Goal"></a>
The primary goal of this project is to create a recommender system that can accurately predict how users will rate anime titles they haven't watched yet. We will achieve this by combining collaborative filtering and content-based filtering methods, using a comprehensive dataset from myanimelist.net.

Key challenges we will address include:

Data Analysis and Preparation: Cleaning and organizing the dataset to ensure it's suitable for building our models.
Collaborative Filtering: Developing a model that recommends anime based on the preferences of users with similar tastes.
Content-Based Filtering: Creating a model that suggests anime based on the characteristics of the titles a user has already enjoyed.
Hybrid Approach: Integrating both collaborative and content-based filtering methods to enhance recommendation accuracy.
Evaluation and Optimization: Testing our system and fine-tuning it to provide the best possible recommendations.
By tackling these challenges, we'll create a powerful recommender system that not only helps users discover new anime but also enhances their overall viewing experience. This project highlights the impact of machine learning in revolutionizing how we find and enjoy content in the entertainment industry.
## 3. exploratory data analysis <a class="anchor" id="EDA"></a>



## 4. models <a class="anchor" id="models"></a>
## 5. Streamlit<a class="anchor" id="streamlit"></a>

### What is Streamlit?

[Streamlit](https://www.streamlit.io/)  is a framework that acts as a web server with dynamic visuals, multiple responsive pages, and robust deployment of your models.

In its own words:
> Streamlit ... is the easiest way for data scientists and machine learning engineers to create beautiful, performant apps in only a few hours!  All in pure Python. All for free.

> It’s a simple and powerful app model that lets you build rich UIs incredibly quickly.

[Streamlit](https://www.streamlit.io/)  takes away much of the background work needed in order to get a platform which can deploy your models to clients and end users. Meaning that you get to focus on the important stuff (related to the data), and can largely ignore the rest. This will allow you to become a lot more productive.  

##### Description of files

For this repository, we are only concerned with a single file:

| File Name              | Description                       |
| :--------------------- | :--------------------             |
| `base_app.py`          | Streamlit application definition. |


#### 5.1 Running the Streamlit web app on your local machine

As a first step to becoming familiar with our web app's functioning, we recommend setting up a running instance on your own local machine. To do this, follow the steps below by running the given commands within a Git bash (Windows), or terminal (Mac/Linux):

- Ensure that you have the prerequisite Python libraries installed on your local machine:

 ```bash
 pip install -U streamlit numpy pandas scikit-learn
 ```

- Navigate to the base of your repo where your base_app.py is stored, and start the Streamlit app.

 ```bash
 cd 2401FTDS_Unsupervised_Learning/Streamlit/
 streamlit run base_app.py
 ```

 If the web server was able to initialise successfully, the following message should be displayed within your bash/terminal session:

```
  You can now view your Streamlit app in your browser.

    Local URL: http://localhost:8501
    Network URL: http://192.168.43.41:8501
```
You should also be automatically directed to the base page of your web app. This should look something like:

<div id="s_image" align="center">
  <img src="https://github.com/karabo/2401FTDS_Unsupervised_Learning/blob/main/Streamlit_image.png" width="850" height="400" alt=""/>
</div>


#### 6.2 Deploying your Streamlit web app

- To deploy your app for all to see, click on `deploy`.
  
- Please note: If it's your first time deploying it will redirect you to set up an account first. Please follow the instructions.
  ## 7. Conclusion and insights<a class="anchor" id="Conclusion and insights"></a>
  ## 8. Team Members<a class="anchor" id="team-members"></a>

| Name                                                                                        |  Email              
|---------------------------------------------------------------------------------------------|--------------------             
| [Karabo Mathibela](https://github.com/karabomathibela)                                                | karabomathibela44@gmail.com
| [Keneilwe Rangwaga](https://github.com/keneilwerangwaga)                                                  |patricia001105@gmail.com |                           
| [Mahlatse Lelosa](https://github.com/mahlatselelosa)                                                                            | mahlatselelosa98@gmail.com
| [Josephina Ndukwana](https://github.com/josephinandukwana)                                                | angelndukwani91@gmail.com
| [Koena Macdonald](https://github.com/koenamacdonald)                                       | kmahladisa9@gmail.com
| [Muwanwa Tshikovhi](https://github.com/muwanwatshikovhi)                                                                   | tshikovhimuwanwa@gmail.com





 
