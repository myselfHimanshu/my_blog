---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /
---

# 👋 Hi, I am Himanshu Panwar

Data Science, Machine Learning, Computer Vision, and Teaching are my passion. This blog is an extension of my passion in helping students and data enthusiast learn about Data Science and how it can be used to make sense of data. 

<hr>

<center><h2>Latest Posts</h2></center>

<ul class="home-bullets-posts">
    {% for post in site.posts limit: 5 %}
    <li>
        <a href="{{ post.url | relative_url }}" class="post-preview">{{ post.date | date_to_string }} &nbsp;&nbsp; ‧ &nbsp;&nbsp; {{ post.title }}</a>
    </li>
    {% endfor %}
</ul>

<hr>

<center><h2>Github Repos</h2></center>

- [Computer Vision State Of The Art Algorithms Project in Pytorch](https://github.com/myselfHimanshu/ultron-vision)
- [Food Ordering Chatbot using Rasa](https://github.com/myselfHimanshu/food-ordering-chatbot)
