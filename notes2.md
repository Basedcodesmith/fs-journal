9/21
1. Wireframing on figma
2. Use select tool to make rectangle for a header and a square for a nav bar. Choose font with text selector on the top left of the screen.
3. Cntrl G to group made shapes to move whole group around.
4. Use select tool to make a hero section in the main. This will take up most of the page.
5. Use Unsplash to find images for each body section. Header, main, footer.
6. Use select tool to make another box to place text in. Put this box in the hero. Make another box to go inside this one to act as a paragraph under the first boxes header. Effects on right side after hitting text button in top left.
7. Put blur/shadow under text in boxes for yummy visual effect.
8. Group everything in hero section with cntrl g to group everything together.
9. Add button under hero text box. Make button with select rectangle again and name it a button. Add text box and put in button to name it.
10.  sub group button box and button text to be able to move whole button around.
11. Put 3/4 boxes using the selector tool in a new row under the hero. Put these boxes in a rectangle that spans the width of the page.
12. Add icons to the above boxes next to the text.
13. group all 3/4 boxes
14. Make footer box with color to match header. Copyright ur stuff in the bottom to troll.
15. Now mock for mobile with a phone frame....cringe.
16. Remake mock on mobile frame by putting all boxes inside it. Make website look good vertically. Find portrait pics. 

    MILES SECTION

1. To code mock, create file in terminal. In html head, link bootstap THEN css with <link href> then <link rel>
2. In the body, create your header with <header class="container-fluid"> then make your <section class= "row">, then put <nav class= "col-12 col-md-6"> 
3. Nest your <span class="fs-3"> tag inside the column and put the name of the header inside the <span class="fs-3">
4. Either by using a bootsrap class in html or assigning a color to a class in css; change your background color in you <span> tag. Depending on how much space you want to change colors, move the color selector to parent for more color, and down thru children for less.
5. Make text color change with a .text-'insertcolor' class inside the <span> tag.
6. Add padding to <span> tag by making tag look like: <span class="fs-3 text-color p-3">
7. Main section
8. <main class="container-fluid">
     <div class="row heroImage">
     <div class="col-12">
9. Make .heroImage class selector. In row in html, put heroImage inside the class. In css, put .heroImage{
    background-image: url(link)
    height: 75dvh
    background-size: cover; Makes it less blurry, shows whole image in that 75dvh
    background-position:top; centers the picture more towards the top.
}     
10. Make sure to </div> for each tag made thus far
11. <main class="container-fluid">
     <div class="row heroImage-text-Bg text-color p-5 justify-content-end">
     <div class="col-2">
     <span class= "fs-2">  shop now! </span> <i class="mdi-spin">
     <p> loremipsum  </p>
    </div>
    </div>
    </main>

     .heroImage-text-Bg is a new css selector for background backdrop. .heroImage-Bg{
        background-color: color;
        backdrop-filter: blur(10px) for bg filter opacity
     } 

     In css use postion relative and

     .product-bgPicture{
        background-image: url(url);
        height: no.;
        background-position: no.rem;
     }

     .shop-button{
        position:absolute
        left: 0;
     }

     @media(max-width: 990px){ put at bottom so this isnt overridden
        .heroImage{
            background-image: url( 'url')
        }
     }