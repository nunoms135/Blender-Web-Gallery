# Blender Web Gallery 
Just make a fun stuff

## How To Open (Option 1)

1. Open the folder
2. Type cmd in the file address bar
3. Once the cmd is open and type (cmd .)
4. Then run the Live Server

## How To Open (Option 2)
1. Open Visual Studio Code
2. Then select the folder
3. Run the Live Server

## Additional Assets / Frameworks
- Slider: [bxSlider](https://bxslider.com/)
- Icons: [Font Awesome](https://fontawesome.com/)

## Insert image with different resolution

Change this

```CSS
.gallery {
    display: grid;
    grid-template-columns: repeat(6, 305px); /* 2 columns */
    grid-template-rows: repeat(2, 305px); /* 2 rows */
    gap:  5px 10px; /* Space between images */
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}

.gallery img {
    width: 305px; /* Set fixed width */
    height: 305px; /* Set fixed height */
    object-fit: cover; /* Maintain aspect ratio */
    border-radius: 20px;
    margin-bottom: 5px;
}
```
