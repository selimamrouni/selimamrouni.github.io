---
layout: defaults/page
permalink: index.html
narrow: true
---


{% include components/intro.md %}

[More about me.]({{ site.baseurl}}{% link _pages/about.md %})

### What else?

This Fall 2018, I am holding four positions at a time. 

I am part-time <b>Research Engineer</b> at <b>NYU Langone Health</b> where I conduct research in order to improve patient-care processes through the use of predictive modeling and optimization methods. 

I appreciate transmitting my knowledge to students as <b>Teaching Assistant</b> in [(PhD) Computing for Business Research](https://www8.gsb.columbia.edu/courses/phd/2018/fall/b9122-001){:target="_blank"} and <b>Course Assistant</b> in Deep Learning at <b>Columbia</b>. 

I also recently joined a <b>research project</b> at <b>Columbia University Hospital</b> in Biomedical Informatics in which I hope to apply my data science knowledge to the medical purpose.

Strong advocate of learning by doing, I am also working on several side-projects which strengthen my skills [The full list is here]({{ site.baseurl }}{% link list/projects.md %}). 

I also recently started writting stories on [Medium](https://medium.com/@selimamrouni){:target="_blank"}, you can also find [all posts by year here]({{ site.baseurl }}{% link list/posts.html %}).

When I have free time, you can also find me running at Central Park, exploring the city, and probably trying some new cooking recipes.



<div class="card-columns">
    
    <div class="card">
        <img class="card-img-top" src="./theme/img/home_page/grad1.jpg" />
        <div class="card-text">Graduation Ceremony - Columbia University 2018</div>
    </div>

    <div class="card">
        <img class="card-img-top" src="./theme/img/home_page/earth.jpg" >
        <div class="card-text">One of my favorite place</div>
    </div>

    <div class="card">
        <img class="card-img-top" src="./theme/img/home_page/overlap.jpg" >
        <div class="card-text">Capsule Network and overlapped MNIST</div>
    </div>


    <div class="card">
        <img class="card-img-top" src="./theme/img/home_page/macaron.jpg" >
        <div class="card-text">Macaron Attempt</div>
    </div>

    <div class="card">
        <img class="card-img-top" src="./theme/img/home_page/model_evaluation.jpg" >
        <div class="card-text">Performance Evaluation</div>
    </div>
     <div class="card">
        <img class="card-img-top" src="./theme/img/home_page/authors2.jpg" >
        <div class="card-text">Let's do some NLP</div>
    </div>

    <div class="card">
        <img class="card-img-top" src="./theme/img/home_page/capsnet_cnn.jpg" >
        <div class="card-text">Capsule Network & Stock Prediction</div>
    </div>

    <div class="card">
        <img class="card-img-top" src="./theme/img/home_page/RLarchitecture.jpg" >
        <div class="card-text">Deep Reinforcement Learning Architecture</div>
    </div>

     <div class="card">
        <img class="card-img-top" src="./theme/img/home_page/patient_flow.jpg" >
        <div class="card-text">Hospital Patient Flow </div>
    </div>


    <div class="card">
        <img class="card-img-top" src="./theme/img/home_page/marathon.jpg" >
        <div class="card-text">Paris Marathon 2016</div>
    </div>

     <div class="card">
        <img class="card-img-top" src="./theme/img/home_page/ensemble_model.jpg" >
        <div class="card-text">Ensemble Modeling</div>
    </div>
     <div class="card">
        <img class="card-img-top" src="./theme/img/home_page/flatiron.jpg" >
        <div class="card-text">New York City</div>
    </div>

</div>




### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}



