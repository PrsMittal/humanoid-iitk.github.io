---
title: Meet My Creators
layout: blog 
description: Forsighted minds drivng the future!
image: assets/images/blog.jpeg
nav-menu: true
# permalink: /team/
---
<div class="container">
<!-- <h2 class="button special big fit">Team President</h2>
<div class="row" style="padding-left:750px">
        {% for slot in site.data.team %}
        {% if slot.type=="0" %}
        <div class="col-md-4">
            <div class="boxes">
                <img src="assets/images/{{slot.image}}" alt="">
                {}
                <h2 class="title">{{slot.description}}<br>{{slot.room_no}}<br>{{slot.hall}}<br>{{slot.phone_no}}<br>{{slot.emailid}}</h2>
                <ul class="icon">
                    <li><a href="{{slot.fb_link}}"><i class="fa fa-facebook-f"></i></a></li>
                    <li><a href="{{slot.git}}"><i class="fa fa-github"></i></a></li>
                    <li><a href="{{slot.linkd}}"><i class="fa fa-linkedin"></i></a></li>
                </ul>
            </div>
            <a class="button special fit">{{slot.name}}</a>
        </div>
        {% endif %}
       {% endfor %}
</div> -->
<!-- <hr> -->
<h2 class="button special big fit">Team Heads</h2>

<div class="container">
    <div class="row" style="padding:50px;padding-left:100px">
        {% for slot in site.data.heads %}
        <div class="col-md-12">
            <div class="boxes">
                <img src="assets/images/team/{{slot.image}}" alt="">
                {}
                <h2 class="title">{{slot.room_no}}<br>Hall {{slot.hall}}<br>{{slot.phone}}<br>{{slot.email}}@iitk.ac.in</h2>
                <ul class="icon">
                    <li><a href="https://fb.com/{{slot.fb}}"><i class="fa fa-facebook-f"></i></a></li>
                    <li><a href="https://github.com/{{slot.github}}"><i class="fa fa-github"></i></a></li>
                    <li><a href="https://linkedin.com/{{slot.linkedin}}"><i class="fa fa-linkedin"></i></a></li>
                </ul>
            </div>
            <a class="button special fit">{{slot.name}}</a>
        </div>
       {% endfor %}
   </div>
</div>
<hr>
<h2 class="button special big fit">Team Members</h2>
<div class="container">
    <div class="row" style="padding:50px;padding-left:100px">
        {% for slot in site.data.teams %}
        <div class="col-md-4">
            <div class="boxes">
                <img src="assets/images/team/{{slot.image}}" alt="">
                {}
                <h2 class="title">{{slot.room_no}}<br>Hall {{slot.hall}}<br>{{slot.phone}}<br>{{slot.email}}@iitk.ac.in</h2>
                <ul class="icon">
                    <li><a href="https://fb.com/{{slot.fb}}"><i class="fa fa-facebook-f"></i></a></li>
                    <li><a href="https://github.com/{{slot.github}}"><i class="fa fa-github"></i></a></li>
                    <li><a href="https://linkedin.com/{{slot.linkedin}}"><i class="fa fa-linkedin"></i></a></li>
                </ul>
            </div>
            <a class="button special fit">{{slot.name}}</a>
        </div>
       {% endfor %}
   </div>
</div>
<hr>