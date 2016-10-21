# Static Web Mastery Exercise - HTML/CSS

First Mastery Exercise for the Static Web milestone during Evening Cohort 3. Overall goal was to create a website in HTML and CSS that met specfic criteria. Testing overall familiarity with topics covered up until this point.

==============================

- Viewing/Downloading Project
    - [To View Hosted Project](#to-view-hosted-project)
    - [Installation](#installation)
    - [To Run](#torun)
- Specifications and Project Information
    - [Languages] (#languages)
    - [Tools] (#tools)
    - [Specifications] (#specifications)

==============================

## Viewing/Downloading Project

### To View Hosted Project

[Static Web Mastery Exercise - HTML/CSS](https://mb-nss-exercises.firebaseapp.com/html-css/index.html)

### Installation

Clone the repository from GitHub:

`git clone https://github.com/mattbruton/StaticWeb-MasteryExercise-HTML-CSS.git`

Navigate to the project from the directory it was cloned into:

`cd StaticWeb-MasteryExercise-HTML-CSS/`

### To Run

If you need a command line http server, to install http-server globally:

`npm install http-server -g`

Then:

`http-server` or `http-server -p XXXX` (the X's represent the port of your choice)

You should now be able to open your browser and type `localhost:8080` to view the project.

## Specs and Project Information

### Languages

1. HTML
1. CSS

### Tools

1. [Git](https://git-scm.com/)
1. [Atom](https://atom.io/)
1. [NPM http-server](https://www.npmjs.com/package/http-server)

### Specifications

==============================

Your task is to build a grid of cards for a company's products. Here's the requirements for the basic structure of the cards.

1. Each card should be an `article`.
1. Each card should take up 30% of the width of the browser window.
1. Each product should contain a `header` element that, itself, contains an `h1` element where the product's title will be written.
1. Each product should have three sections.
1. The first section should contain three child block elements.
    1. The first element contains the product image.
    1. The second element contains the product description.
    1. The third element contains the product availability (e.g. "Available" or "Not Available")
1. The second section contains product specifications.
    1. This section should have a header containing the word "Specifications"
    1. This section should contain two block elements
    1. The first block element specifies the size.
    1. The second block element specifies the weight.
    1. This section should contain a footer.
    1. The footer contains text stating when the product specifications become invalid.
1. The third section contains the product pricing.
    1. This section should contain a header.
    1. This section should contain three block elements.
    1. Each block element contains information about the price for different quantities.

### Additional style requirements

1. The entire card has a solid 1px border that is light blue.
1. The card title has a dotted 1px border that is light grey.
1. The title and product image are centered.
1. Notice that the text for the description in the image is justified.
1. The text for the product specification details and pricing details is bold.
1. The availability element extends the full width of the card, with a dark grey background and yellow text.


==============================