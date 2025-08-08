# Staging Site for The Heron Center

This repository holds the source code for The Heron Center staging site.

## About

## Development

To set up your environment to develop this theme, clone this repo or your fork.

```sh
$ git clone https://github.com/eastofesten/heron.git
$ cd heron
```

Then run:

```sh
$ bundle install
```

To test the theme, run this. (Using the `--trace` flag for verbose errors.)

```sh
$ bundle exec jekyll serve --trace
```

Then open your browser at:

- http://localhost:4000

Add pages, documents, data, etc. like normal to test the theme's contents. As you make modifications, your site will regenerate and you should see the changes in the browser after a refresh.

## License

The [Agency Jekyll Theme](https://github.com/raviriley/agency-jekyll-theme) is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

This license does NOT include any objects or images used in the site or external dependencies included in the `assets` directory, which are covered by their individual licenses.

## Making Changes

### I want to change…

The Home page: **pages/index.md**

*   The Carousel: **\_includes/new-carousel.html**. Images need to be listed here and added to the **assets/img/carousel/revised** folder. 
    
*   The About Us:  **\_includes/about.html**
    
*   Spaces: **\_data/sitetext.yml** 
    
*   Get Involved: **\_data/sitetext.yml**
    
*   The Footer: **\_includes/contact-us.html**
    

The About page: **pages/about.md**

*   The Timeline (check the image URL here): **\_data/sitetext.yml**
    
*   The Board Members: **\_data/sitetext.ym**l
    
*   The Annual Report: **pages/about.md**
    

The Spaces page: **pages/spaces.md**

*   The carousel: add new images to either **assets/img/spaces/fallriver** or **assets/img/spaces/westport**. 
    

The Partners page: **pages/partners.md**

The Programs page: **pages/programs.md**

*   Adding a new program: Add a new .md file to the **pages/programs** folder. At the top, include the following information: 
    

\---

layout: page

title: 

subtitle:

image:

alt:

categories: programs

description:

permalink:

location: (either “fall river” or “westport”)

when:

contact:

tuition:

type: programs

\---

Below the three dotted lines, add any additional text you would like to appear on the page. Place the image in the **assets/img/programs/\[folder with the name of the program\]**.  

The Events page: pages/[events.md](http://events.md)

*   The carousel: add new images to the **assets/img/events/events-carousel** folder.
    

The Classes page: **pages/classes.md**

*   Adding a new class: Add a new md file to the **pages/classes** folder. At the top, include the following information: (a file, the text, an image)
    

\---

layout: page

title: 

subtitle:

image:

alt:

categories: classes

description:

permalink:

location: (either “fall river” or “westport”)

when:

contact:

tuition:

type: class

\---

Below the three dotted lines, add any additional text you would like to appear on the page. Place the image in the **assets/img/classes/\[folder with the name of the class\]**.  

The Support page: **pages/support.md**