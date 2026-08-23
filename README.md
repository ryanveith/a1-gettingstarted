Assignment 1 - Hello World: Basic Deployment w/ Git, GitHub, Render

Ryan Veith
https://a1-gettingstarted-w0cm.onrender.com/

This project shows a simple Webpage with some information about me. It a variety of simple html and css and is hosted on render at the above link.

## Technical Achievements
- **Styled page with CSS**: I added rules for the website in general, the navigation section, the list of classes as well as the headers.
The navigation section is alligned to the right of the page and the individual links themselves have padding and a background color to make them fit in better with the rest ofthe website
The website in genreal or the body has its font set to Roberto from the google font family as well as the background and text colors set to colors from my color pallete
The list has a different backgound color and text color using two other colors from my color pallete, it also has a border in the same color as the text color. The width of the list is also set so that the backgound does not span the full width of the page. Finally the individual list items were given a gap so that the list as a whole looked less cramped
The headers have additional text decoration in the form of an overline and underline. They also have the same backround color as the list, but use the last color from my color pallate as the text color, they also have some padding so that the overline fits within the background and a border. 
I also added background color, padding, and text aling to make them both stand out more and be more readable.
The reason this was challanging was finding CSS styles to add that were 1 unique since there needed to be five different ones, 2 have a visual change that did not look horrible, and 3 not something that was already a requirement for a different achivment.

- **Simple JavaScript Animation**:
It is basically a screensaver animation. The smaller box bounces around with some randomness on the new direction when it hits the edge of the bigger box. It also follows the color scheme, the bigger box is #0085B8 small box is #B84100.
The biggest challage with the animation was the setInterval function. It was not one I was familear with. I also needed to look how transform worked because I have not used it before, and it did not help the my first instincts are to put in all the wrong directions becasue I can never remember what is cordinate (0,0) because I keep inverting y in my mind. 

- **Other HTML tags**: I added a header, links, a list, an image and a footer
The header contains the nav tag and has links to the various parts of my page
The past classes part of my webpage contains an unorderd list where each list item is a class
The Color Scheme of this Website has an image of the color wheel with the split complementary color harmony. The biggest challange here was getting the image to work. I remembered all the tags and how to use them, but I was used to working with Express so it took me a bit to realize I needed to turn the image into a base64 string. 

## Design Achievements
- **Used a color palette from color.adobe.com**: I used the all 5 colors from my color pallete in the website. The first one #B87A00 which is the bright orange is the backound. Of the two darker colors the dark blue #1C3038 is the main text color. The darker orange #B84100 is the background for the list, links and headers. The dark brown #382F1C is the text color of the list and also the boarder color. Finnaly #0085B8 the light blue is the text color of the headers. You can see screenshots of the color pallete in the images folder, alternativly there is an image displayed under the Color Pallete For this Website header. This was all smooth sailing to implement, only issue with it was I wanted to display it as an image instead of just have it but a quick conversion to base64 later and it worked.

- **Used the Roboto Font from Google Fonts**: I used Roboto font from google fonts as the font-family for the entre website. It is linked using the exact code given from the Google Fonts website to do so and then then I set the font family in the body. I was a bit worried thinking that this might be a repeat of the image error but ti actually worked just fine. The google fonts website has the code to needed to load the font:
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
And after that Roboto suddenly just worked as a font-family.