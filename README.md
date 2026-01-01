# WEB102 Prework - Sea Monster Crowdfunding

Submitted by: **Samuel Alemu**

**Sea Monster Crowdfunding** is a website that displays information about the games funded by the company. It shows stats, top-funded games, and allows filtering based on funding status.

Time spent: **30** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] The introduction section explains the background of the company and how many games remain unfunded.
- [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
- [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding.
- [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

- [x] Improved UI styling with card shadows, hover effects, and layout enhancements.

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with ...

## Notes

During this project, I encountered and solved a few challenges:

- **Understanding dynamic DOM updates:**  
  I had to ensure that each section re-rendered correctly when filtering games. This required using the `deleteChildElements()` function before adding new content.

- **Learning `reduce()`, destructuring, and the spread operator:**  
  These JavaScript tools were new to me, so calculating summary statistics and selecting the top-funded games took some trial and error.

- **Fixing typos and logic bugs:**  
  Small issues like using `toLocaleString()` correctly or referencing missing variables (e.g., `totalGames`) caused unexpected behavior, but debugging them helped strengthen my skills.

- **Improving CSS styling for readability:**  
  Some text initially blended into the background, so I adjusted colors, shadows, and layout to make the site more visually appealing.

- **Preventing duplicate game cards when filtering:**  
  I learned why clearing the container first was important, otherwise every button click kept adding more cards instead of replacing them.

Overall, the project helped me gain confidence with DOM manipulation, modern JavaScript methods, and UI improvements.


## License

Copyright 2025 Samuel Alemu

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
