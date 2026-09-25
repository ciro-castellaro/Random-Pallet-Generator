# HOW TO USE THE WEBSITE

1- Select the number of palettes to generate (6, 8, or 9)

2- Select the color code format to generate (HEX or HSL)

3- Once both options are selected, click the "Generate Palette" button to create the desired number of random colors

## HOW TO COPY COLOR CODES TO THE CLIPBOARD

1- Move the cursor over the color you want to copy and left-click on it

2- A Toast notification will appear at the bottom of the page confirming that the color was successfully copied

3- Paste the color wherever you want to use it

## TECHNICAL DECISIONS

### 05/20/2026

```
HTML, CSS, and JavaScript are separated into different files to keep the code more organized and easier to maintain.

CSS variables are used to manage colors and make future design changes easier.

Responsive units such as `rem` are prioritized to improve visual adaptability.
```

### 05/21/2026

```
A dark color palette using black, gray, and blue tones is chosen to create a more modern and visually comfortable aesthetic.

HEX and HSL color formats are supported to provide users with more flexibility depending on how they want to use the palette.

A simple and minimalist interface is maintained to make palette generation fast and intuitive.

JavaScript is used to dynamically generate random colors without requiring the page to be reloaded.

A color-copying feature is implemented to improve the user experience.
```

### 05/22/2026

```
A Toast notification system is added to display visual messages without interrupting the user experience.

Colors are generated completely randomly to increase palette variety.
```

## HOW TO RUN AND DEPLOY THE WEBSITE

### Running Locally

1- Download or clone the repository

In Git Bash, run the following command:

`git clone REPOSITORY_URL`

2- Open the project folder

3- Install the Live Server extension for Visual Studio Code

4- Open the `index.html` file and click the "Go Live" button in the bottom-right corner

### Deploying the Website

The website can be deployed using free services such as:

* GitHub Pages
* Netlify
* Vercel

### General Deployment Steps

1- Upload the project to GitHub

2- Connect the repository to the deployment platform

3- Publish the website automatically
