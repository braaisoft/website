---
layout: default
title: Retail Business Software Solutions
class: front
---
        
<div>
    <a href="{{ BASE_PATH }}">
       <img src="{{ BASE_PATH }}/assets/images/braaisoft-logo_671x100.png" class="img-responsive" alt="Braaisoft" style="margin: 2.4em 0 1.6em 0;" />
    </a>
</div>

<div class="row" style="position: relative;">
    
    <div class="col-md-9">

        <h1 class="jumbo-lead">We solve retail business problems with software.</h1>
    
        <p class="lead">
            <strong>Braai</strong> is a traditional South African social gathering around an open fire. It represents the shared joy, laughter and merriment of cooked food over warm coals.
            <a href="about.html">Learn more about Braaisoft</a>.
        </p>
        
        <h2>Recent Posts</h2>
        
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
        
    </div>


    <div class="col-md-3" style="margin-top: 1.62em;">
    <div class="well">
    <h3 class="text-center" style="margin-top:0;">We're Hiring!</h3>
    <div class="text-center">
    <img src="{{ BASE_PATH }}/assets/images/good-old-braai.jpg" class="img-responsive img-center img-rounded" /></div>
    <p class="text-center1 text-muted1">Do you love Clojure / ClojureScript? Do you love to braai?</p>
    <p><a class="btn btn-success btn-sm" href="{% post_url 2015/2015-02-12-hiring %}">Apply at Braaisoft</a></p>
    </div></div>

</div>

