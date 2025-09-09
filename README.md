# 🎯 User-Empowered Anime Recommender

For my [Metis](https://www.thisismetis.com/data-science-bootcamps) final project, I developed an **interactive anime recommender system** that helps users discover personalized anime recommendations. This project addresses the business problem of **matching users with content they are likely to enjoy**, which is crucial for platforms like MyAnimeList or streaming services that rely on user engagement for growth and monetization.

The recommender combines **content-based filtering** (analyzing anime features like genre, episodes, and ratings) and **collaborative filtering** (leveraging patterns from similar users). Users can select how **adventurous** they want their recommendations to be:  

- **More adventurous**: Higher weight on collaborative filtering to suggest lesser-known or unexpected titles.  
- **More conservative**: Higher weight on content-based filtering to suggest titles similar to the user's past preferences.  

By giving users control over recommendation type, the system improves engagement and satisfaction, which is a key business driver for anime platforms.

To learn more about the methodology, see my [blog post](https://binhhoang.io/blog/anime-recommender/).  

*Images and data were sourced from the internet for educational purposes.*

---

## 📋 Table of Contents

* [Screenshots](#screenshots)
* [Business Problem](#business-problem)
* [Features](#features) 
* [Technologies](#technologies)
* [Setup](#setup)
* [About Metis](#about-metis)

---

## 📷 Screenshots

**Flask Home Page**  
![Flask home page](https://user-images.githubusercontent.com/62628676/97792286-b8978b00-1bb2-11eb-8a9d-7df79a578d28.png)

**Recommender Page**  
![Flask recommender page](https://user-images.githubusercontent.com/62628676/93409135-33efe800-f864-11ea-9c10-0396cda3428d.png)

---

## 💼 Business Problem

Anime platforms and streaming services face the challenge of **keeping users engaged** by recommending content that aligns with their tastes. Poor recommendations can reduce user engagement and limit revenue opportunities.  

This project addresses the question:  

> *How can we deliver personalized anime recommendations that balance familiarity with exploration to increase user engagement?*

By combining content-based and collaborative filtering, the system helps:  

- Users discover **anime they are likely to enjoy**  
- Platforms increase **user engagement and retention**  
- Platforms surface **lesser-known anime** effectively  

---

## ⚡ Features

* Generate **personalized anime recommendations** for a MyAnimeList user ID  
* Adjustable recommendation type: **“adventurous” vs “conservative”**  
* Combines **content-based** and **collaborative filtering**  
* Recommendations are dynamic and reflect both **user taste and broader trends**

> ⚠️ Only works for anime and user IDs scraped from MyAnimeList.net.

---

## 🛠 Technologies

- **Programming Languages & Tools:** Python 3.8, HTML5, CSS3  
- **Frameworks:** Flask 1.1.2  
- **Web Scraping:** BeautifulSoup 4.9.1, Selenium 3.141.0  
- **Deployment & Cloud:** Docker 19.03.12, Google Cloud Compute Engine  
- **Database:** MongoDB 4.4.0  
- **Data Analysis & Machine Learning:** Scikit-learn 0.23.1, Pandas 1.0.5, Numpy 1.18.5, Seaborn 0.10.1  

