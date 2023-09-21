Date: 9/19
 1. create directory in terminal. Week by week folder for projects/checkpoints, source/codeworks/ mkdir 9/19 project, cd into directory
 2. mkdir petcare, cd into petcare
 3.touch index.html
 4.touch style.css
 5. link style sheet under head in html. <link rel= style.css
 6. open petcare file in css. / cntrl shift p = settings.json peacock.color blue cntrl comma = settings cntrl p = find file cntrl x to delete line cntrl y = redo windows . = emojis
 7.! + enter = boilerplate / turn on format on save bcw serve in terminal to run mock code
 8. title under head, "petcare" title changes tab name in browser
9.  3 html sections, semantic tags. Header, main, footer/top middle bottom Everything is encompassed in the body tag, header, main, footer. Use chrome inspect. display: block = things will be able to stack on eachother.
10.  span tag inside the header to put content between the opening and end of the head. Displays inline, horizontally .
11. Inside header put p tag with content within. Use p instead of h1 for reg text size on head of the page.
12. In css write styles to apply spacing for head tag. select with header element in css
13. Under css header tag use padding property. nopx = y axis nopx = x axis, left, right,
14. add color under header
15. add class selector to html p tag. this way you dont select all p tags in css by accident
16. under class "title" in css, change font-size. Remember, class selectors need a period. em instead of px for font.
17. under class "title" add border-bottom for border under the header. add px size and color
18. Add padding under "title"
19. In html, under main, add an h1 for a header in the middle of the screen. html/header/ i tag/ class="mdi"
20. to assign padding to all header, main, and footer, change padding under body tag in css
21. /* section the css page to make it look neat. to move lines in vs code, select line then hit alt + up/down
22. in css, under main tag, put margin-top and add padding outside of main. use vh, not px. vh = view height
21. in html/body/main/ p tag with content under h1 for paragraph text. Put lorem in p tag for mock content
22. Make button in body. html/body/main/ under p tag make button tag that reads "our services" add class selector inide of button tag that reads "service button"
23. Make second button in html/body/main/ under first button put button tag that reads "get in touch 📞 ⚙️⚙️⚙️⚙️⚙️"
24. add space between buttons in css with margin under "service button" class selector
25.  html/body/main/ under second button put img tag. put in src and alt content. Remember, img tags have no closing. Use Unsplash for img's copy img url for img src. Make sure its in quotes. 
26. Position dog img in css. Css/img tag selector/ max height 40-60 vh. dont use px
27.  In css/main tag/ put display flex. Make block container by selecting everything in html main and alt it up into div tags
28. inside the div tags surrounding "main" content, put class = "hero". Main section is the "hero" of the webpage.
29. In css/ .hero-text selector/max- width 40 vh. Align content in chrome inspector with "justify content" and "align"
30. Under html/footer/ text content. Put padding in main and header instead of body lmaooo. this way footer bg color wraps correctly
31. under css/body tag/ set margin to zero so theres no accidental space
32. css/footer tag/ background-color: choose mock color
33. html/footer/ h2 tag. dont use same sized tags. use h's in descending order.
34. html/footer/h2/ "pups" 🐶 make h2 pups class 
35. css/.pups/color: white or change all text just under css/footer tag
36. css/footer/padding 41px alt + shift + down/up in html to move stuff put each h2 inside its own div tags
37. add under html/footer/h2 for rats, and cats.
38. in css/footer/add display.
39. add a class selector to each respective h2 in html/footer
40. in css/ put : footer > div/ padding: 80px
41. css/footer/margin top to seperate img from footer
42. htm/body/head/ under p tag add nav tag. in nav tag put each header item in its own p tag
43. css/nav/display:flex to get the 42. p items side by side
44. html/body/head add new p tag under nav
45. css/ nav > p/margin 5px
46. for shadows put "text-shadow" under preferred class or element selector. "box-shadow" for img tags use px. "border-radius" under img tag to round things
47.  

    9/20
1. Bootstrap. for grids that are the same from the smallest of devices to the largest, use the .col
2. containers hold rows, rows hold columns. Split header, main, and footer into containers on figma
3. Use rows to breakup containers into smaller sections, put columns inside the rows. columns = .col
4. create freelancer in cmd. touch html/css
5. link: bs5 will link bootstrap to your html 
 6. html/body/<header class = "container bg-primary sticky-top"> sticky-top makes element stick to parent element
 7. html/body/<div class = "col-12 p-1"  > .col-2 will make the col line with div and everything p-1 thru 5 = padding m-1 thru 5 for margins 
 8. <div class = "container-fluid"> will take up whole page without padding. No white space.
 9.  Do not nest columns within columns, or rows within rows 
 10. <div class = "col-12 fw-bold fs-4"> fw= font weight fs= font size
11. <section class= "row align-items-center"> align with align class
12. <button class ="btn btn-success d-none d-md-block"> d-none= no display
<!--SECTION Main -->
13. <main class= "container-fluid">
14. <!--SECTION hero--> cntrl/
14. <section class= "row"></section> 
<!--SECTION hero -->
<div class= "col-2"> 
<img src ="" alt= "">
</div>
<!--!SECTION portfolio-->
<section class= "row"></section>
<div class ="col-12 col-md-4 col-lg-3" > cntrl v on line to edit all same lines. put breakpoint: 'col-md-x' within col class to change for specific device
<img class= "img-fluid rounded" src = "url" alt= cabin> img fluid makes img not exceed the page. 'rounded' inside class rounds img
</div>
</section> 
<section class= "row my-4"> my-4: marigin on y axis
<h2> About </h2>
<i class="i=mdi mdi-star">
<p> lorem ipsum </p>
<div class = "col-12"

<!--!SECTION portfolio--> 

<!--!SECTION footer-->
<footer>
<section class= "container-fluid "></section>
<section class= "row"> </section>
<div class= "col-12">
<p class= "mb-0 md-order-1"> About </p>
</div>
<a href="url" target="blank">  </a>


