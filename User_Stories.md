# Final Project Overview: Code MD201-4

## Bites'n Bethesda 

### User Stories

Maslow's Hierachy of Needs lists **food** as one of the basic physiological needs. When the call of nature beckons and hunger strikes, no one wants to be faced with the undaunting task of figuring out _where to eat_. Working through the logistics of satisfying one's hunger is difficult. As modern day _Hunter Gatherers_ this can be further complicated when you have a various palettes to satisfy; i.e. a **family**.

This is where Bites'n Bethesda comes in... let's be honest; sometimes deciding where to eat can be hard. We won't promise to eliminate all the uncertainties, but our solutions are designed to make your _"Hunt"_ a bit little simplier.

**Bites'n Bethesda** provides nutrious and delectable dining options in the Bethesda area; we allow our users to search our database by selecting key _"location features"_ (i.e. Wi-Fi, Vegan options, etc) to enhance your dining experience. To top it off, we will even throw in **recommended parking location(s)** and a **video preview** of your selected dining location... because, yeah we thought of that too!!

## Problem Domain

To create this _"dine-out selection"_ application we enlisted a team of talented development experts. The project stakeholders are as follows:

- `Market researchers`: researches were engaged to conduct market analysis on restaurants within the Bethesda area. Their findings would then highlight the **five (5) top restaurants** in Bethesda; the names of which would be submitted to our development team. _N.B. The analysis is re-initiated every month to provide an updated database for the application_.

- `Videographers/Photographers`: a team of _visionaires_ visited all five locations to shoot eye-catching images and video of the restaurants.

- `UX/UI Designers`: a team of designers will _wireframes_ the layout and user experience components of the project.

- `Developers`: a development team was tasked with the challenge of bringing **Bites'n Bethesda** to life. They are the _brains_ behind the `technical requirements` and innovations of the application.

Once the `marketing team` submits the results from their analysis the `videographers` will go out and capture the _"best views"_ of each restaurant.

`UX/UI Designers` will generate wireframmed sketches and details which will guide development team's formulation of `technical requirements` for the project (_see attached sketches and notes in the project assets folder_).

The application will consist of twp (2) HTML pages with accompanying CSS and JavaScript code to style and drive the interactivity of the application. A master repository `final_bbproject` will be created with accompanying branches: `html-content`; `css-content`; `js-content`. _User Stories_ will be held on the master branch.

The two primary HTML pages are as follows: `index.html` `select.html`. Each HTML page will be styled by its respective CSS page: `main.css` `select.css`. The entire project will be driven by the JavaScript code created in a `select.js` file.

The application will launch on a main page `index.html`. It includes a brief introduction and information about the app. A button titled `continue` will be included which sends the user to the selection page `select.html`.

The selection page will utilize a `div` with radial selections or `field sets` of restaurant choices. It will then have a second `div` of *features*. The users selections will be held in local storage by clicking on a `submit` button. The `submit` button also initiates a pull from an array of restaurants to display an `image` (_based on the users selections_) of thr recommended dining location.

An associated `video window` will also be displayed below the image to give the user a preview of their *dining selection*. Video will be _no longer_ than 2 mins in length. Finally, the application will reference the *nearest parking location(s)* by `name` and `address`. A snippet from _Google maps_ will be embedded for visual illustration.

N.B. To `reload` or return the application to home a `Home` or `Return to Home` button will be included. **Additionally, the `asset` folder will also house all restaurant images/video and google map snippets relevant to the project.**

