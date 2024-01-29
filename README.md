# Flower Shop Website with ChatGPT Prompts

## Overview
This repository contains the source code for a flower shop website created using HTML and CSS, with dynamic content generated through ChatGPT prompts. The website showcases the florist's services, provides an about us section, and integrates ChatGPT for personalized interactions.

## Main Features
- HTML and CSS-based static website for a flower shop.
- Dynamic content generated using ChatGPT prompts.
- Responsive design for optimal viewing on various devices.

## Getting Started

### Prerequisites
No specific prerequisites are required to run the static website. However, if you plan to modify or extend the ChatGPT prompts, you might need access to the OpenAI GPT-3 API.

### Setup
1. Clone the repository:
   git clone https://github.com/anaidpm/flower-shop-chatgpt/

2. The main code is in `index.html`.

## Prompt Engineering

I used ChatGPT to generate the code and some of the content for this website.

Here's a list of the prompts.

<b> Prompt: I want to create an html website using CSS and HTML for a florist. What information should I highlight on this website? </b>
ChatGPT gave a list of ideas to implement, including: Homepage, About Us, Products/Services, etc.

<b>Prompt: Let's start creating the website using HTML. Create a section with a large image of the florist shop with the title "Welcome" written on top in white. </b>
The result was some code to set up a simple webpage with a header section containing a large image of the florist shop and a "Welcome" title. The styling includes a text shadow to make the title stand out against the image. Adjust the image URL and styling according to your preferences.

<b>Prompt: Next, we need a "Services" section. It will have an h1 title followed by three service boxes with a title a lorem ipsum text.</b>
ChatGPT created three service boxes with the following titles: Flower Arrangements, Event Decorations and Flower Delivery.

<b>Prompt: Can you put appropriate font awesome icons under each service title? </b>
ChatGPT updated the website's head by adding the following:

    ```
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha512-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx" crossorigin="anonymous" referrerpolicy="no-referrer" />
    ```

    This did not work for me. So I replaced it with the following:
```
<link rel="stylesheet" 
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
```
I also replaced some of the `fa` icons with the ones I preferred.

## Next Steps

Work on making the website responsive on mobile.

