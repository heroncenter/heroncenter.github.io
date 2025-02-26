---
layout: gallery
title: Programs at the Heron Center
description: 
image: 
permalink: /programs/
---

In Nature, biodiversity matters for a healthy, resilient and stable ecosystem. Our programs mirror Nature’s wisdom by offering equally diverse educational experiences for creating healthy, resilient and balanced communities.  

 <section id="portfolio" class="bg-light-gray">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center">
                    <h2 class="section-heading">Experience Our Diverse Programs</h2>
                    <h3 class="section-subheading text-muted">All programs are led by professional experienced educators and are specially curated to teach sustainable tools and practices that people can use throughout their lives.</h3>
                </div>
            </div>
            <div class="row">
            {% for post in site.posts %}
            {$ if post.categories contains "programs" $}
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

## Mindfulness and Creative Expression

Our Mindfulness & Creative Expression Programs are uniquely designed to meet the group or individual needs and goals of the people we serve!

Learn to feel good, creatively express, and expand your mind in our mindfulness programs. These programs instruct each person in practices that support wellness and empower the individual. Participants will experience breath techniques, journaling, sound, movement, creative prompts and more.
Live music and other creative artistic expressions may and can be included in program. 

**We have designed programs and are currently working with**: Social Emotional & Neurodivergent Classes in the Fall River Public Schools, Adults living with addiction at the Fall River Comprehensive Treatment Center. Want us to design and lead a program for your group? [Contact us](https://theheroncenter.org/contact-us/)
