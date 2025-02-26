---
layout: gallery
title: Classes
description: 
image: 
permalink: /classes/
notes: i don't think this will be a gallery layout, but two gallery layouts with a drop down, perhaps?
---
# Classes

## Learn to feel good from attending weekly wellness classes that instruct each student in practices that support balance, wellness and cultivate peaceful living. 

The Heron Center takes an active step towards increasing sustainability, ensuring equitable access to education, culture and health in our community! Our educational experiences are based on the philosophy that there is no “one size fits all” approach to wellness. The more you develop awareness of Self, the more you sense freedom and ease of being. Each experience within our space is as unique as the person offering it. Each class aspires to empower the individual with knowledge for safe and sustainable practices that will last a lifetime.

We believe in multi-generational experiences, safe and inclusive spaces for learning.

Learn more about [Our Values]()

 <section id="portfolio" class="bg-light-gray">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center">
                    <h2 class="section-heading">Tuition-Free Classes</h2>
                    <h3 class="section-subheading text-muted">Tuition Free Classes & Programs are made possible by the support from The Squillante Family Trust, our Members and Donations.  Registration is Required to Attend Classes, please see details below. PLEASE RSVP AT MINIMUM 2HRS BEFORE THE START TIME OF THE CLASS, TO ENSURE YOUR REQUEST IS RECEIVED AND SPACE IS AVAILABLE</h3>
                </div>
            </div>
            <div class="row">
            {% for post in site.posts %}
            {$ if post.categories contains "tuition-free" $}
                <div class="col-md-4 col-sm-6 portfolio-item">
                    <a href="#portfolioModal{{ post.modal-id }}" class="portfolio-link" data-toggle="modal">
                        <div class="portfolio-hover">
                            <div class="portfolio-hover-content">
                                <i class="fa fa-plus fa-3x"></i>
                            </div>
                        </div>
                        <img src="img/portfolio/{{ post.thumbnail }}" class="img-responsive img-centered" alt="">
                    </a>
                    <div class="portfolio-caption">
                        <h4>{{ post.title }}</h4>
                        <p class="text-muted">{{ post.subtitle }}</p>
                    </div>
                </div>
                {% endif %}
            {% endfor %}
            </div>
        </div>
    </section>

Want to support tuition free programs & classes.
Donate Today
Or become a Member! 

# Tuition Based Classes

 <section id="portfolio" class="bg-light-gray">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center">
                    <h2 class="section-heading">Tuition-Based Classes</h2>
                    <h3 class="section-subheading text-muted">*Discounts available to Members, Sustaining Members, Youth & Card to Culture eligible members. Registration is Required: A minimum of 2hrs before the start time of each program to required to ensure your request is received and space is available.</h3>
                </div>
            </div>
            <div class="row">
            {% for post in site.posts %}
            {$ if post.categories contains "tuition-based" $}
                <div class="col-md-4 col-sm-6 portfolio-item">
                    <a href="#portfolioModal{{ post.modal-id }}" class="portfolio-link" data-toggle="modal">
                        <div class="portfolio-hover">
                            <div class="portfolio-hover-content">
                                <i class="fa fa-plus fa-3x"></i>
                            </div>
                        </div>
                        <img src="img/portfolio/{{ post.thumbnail }}" class="img-responsive img-centered" alt="">
                    </a>
                    <div class="portfolio-caption">
                        <h4>{{ post.title }}</h4>
                        <p class="text-muted">{{ post.subtitle }}</p>
                    </div>
                </div>
                {% endif %}
            {% endfor %}
            </div>
        </div>
    </section>






