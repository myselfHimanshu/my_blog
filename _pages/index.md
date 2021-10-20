---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
permalink: /
---

<h1> 👋 Hi, I am Himanshu Panwar </h1>

I’m a passionate Software Engineer who loves Machine Learning, Computer Vision, and Data Science. I like teaching and this blog is an extension of my passion in helping students and data enthusiast learn about Data Science. 

{% include newsletter.html %}
<hr>

<center><h2>Full Stack Data Science School</h2></center>

A disciplined, structured, and definitive source for learning and implementing the fundamentals of Data Science and Machine Learning.

{% include fsdss.html %}

<div align="center">

<a href="https://myselfhimanshu.github.io/fullstackdataschool/" target="blank"><img align="center" src="https://img.shields.io/badge/free%20code%20camp-27273D?style=for-the-badge&logo=freecodecamp&logoColor=white" alt="anshupy" /></a>

</div>

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

<center><h2>Github Projects</h2></center>

- [Computer Vision State Of The Art Algorithms Project in Pytorch](https://github.com/myselfHimanshu/ultron-vision)
- [Food Ordering Chatbot using Rasa](https://github.com/myselfHimanshu/food-ordering-chatbot)
