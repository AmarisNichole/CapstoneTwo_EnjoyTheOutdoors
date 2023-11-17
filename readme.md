# Capstone 2: Enjoy the outdoors

Welcome to the Enjoy the Outdoors , an HTML, CSS, and JS project designed to make exploring national parks a seamless experience. Navigate easily through the user interface designed for effortless interaction. Explore diverse content across three pages - Home, and specialized pages for searching by location or type.

## Pages 

### Home

This the landing page for our webiste and it includes navigation and highlights things people can do to enjoy the great outdoors. 

![Home page of website](/screenshots/Screenshot%202023-11-16%20203626.png)

### National Park
![National park page](/screenshots/Screenshot%202023-11-16%20232521.png)

### Mountain info 
![Mountain information page](/screenshots/Screenshot%202023-11-16%20210233.png)

## Interesting Code Snippet
```
 let imgContainer = document.createElement("div");
        let imgBox = document.createElement("img");
        imgBox.src = "/images/" + mountains[index].img;
        imgBox.alt = mountains[index].name;
        imgBox.width = 350;
        imgContainer.appendChild(imgBox);
        imgTagEl.appendChild(imgContainer);
```