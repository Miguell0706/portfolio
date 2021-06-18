# Portfolio-
This homeworks assignment's purpose is to be able to create a portfolio page and have it be responsive by using mediaqueries

## Acceptance/Work Criteria-
This work criteria was taken from the homeowork assignment's Readme.md file. 
```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

![Screenshot (1735)](https://user-images.githubusercontent.com/82692900/122614403-70db4c00-d03b-11eb-92e0-c99103411ff0.png)


## Funcitonality of the program -
The program uses vanilla CSS and HTML to create a responsive portfolio that displays contact information, work, and a responsive navigation bar. A CSS grid was used to 
be able to use layers to styize the hero banner image and make it more appealing. Mediaqueries were used to be able to manipulate the CSS and HTML to prevent the 
content on the page from collapsing when the screen size is minimized. 

## CSS code that made layers to stylize the hero banner 
``` CSS
/*HeroBanner code*/
.heroBannerBox {
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 350px;
  grid-column-gap: 0px;
  grid-row-gap: 0px;
  align-content: center;
  justify-content: center;
}
.heroImageBox {
  grid-area: 1 / 1 / 2 / 2;
}
.heroOverlay {
  grid-area: 1 / 1 / 2 / 2;
}
.heroTextBox {
  grid-area: 1 / 1 / 2 / 2;
}
```

![Screenshot (1737)](https://user-images.githubusercontent.com/82692900/122614587-cc0d3e80-d03b-11eb-8f1d-a19b60949dc3.png)


[Link to my portfolio page!](https://miguell0706.github.io/portfolio/)
