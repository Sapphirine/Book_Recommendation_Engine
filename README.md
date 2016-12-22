# Book_Recommendation_Engine
## Final Project for E6893 Big Data Analytics

Huashu Li(hl2919), Yunfan Zhang(yz2866), Zhuangfei Yang(zy2233)

### Project Description
**Dataset Description**

We use Amazon Books Review data spanning May 1996 - July 2014 from http://jmcauley.ucsd.edu/data/amazon/ .
It is 9 gigabytes containing 8,898,041 reviews (ratings, text, helpfulness votes etc.).

**Project Overview**

Build a recommendation system to recommend new books to customers. This includes recommending books to the existing users based on their tastes and recommending reading list to new users based on books’ popularity. 

Group users based on their similarities and recommend friends to users.

Explore the relationship between reviews and helpfulness. Recommend potential useful reviews.

Visualize the findings through System G and Web application.



### How to Open Web GUI
- Down load FrontEnd folder
- In terminal run
```
pip install flask
pip install requests
unzip Euclidean_Recommendation.json.zip
unzip sorted_avgDict.txt.zip
python app.py
```
- Open http://127.0.0.1:5000/ in any of your browser(Chrome, FireFox, IE)


