This project was for learning how to install and use TailwindCSS.

During this project I have used Tailwind's classes to customise the layout and colours the website use to make a home page. To do this, first I added the Tailwind CSS framework linking to it with src as a script on the head of the HTML file. I later then installed it on a different version using npm commands. From there I arranged the top with a bold title, created a navigation section to the side of the top with links and then coloured the text with features such as setting the text to an emerald colour by adding a class and calling it "text-emerald-100". Text size can also be changed by setting "text-4xl" which sets the text to use Tailwind's extra large size and then makes that four times larger.

Then I created a gallery page with a background gradient going from a dark emerald to a lighter emerald by adding "bg-gradient-to-r from-emerald-400 to-emerald-100" with bordered images in a row along the page.

I found installing Tailwind through using npm to be particularly challenging as I encountered several issues, including as it turned out, that tailwind had updated to version 4 and with that the commands to install it had changed. This also then changed the method to add custom colours, going from being added in config.js to then being added in input.css underneath "@import "tailwindcss";" followed with adding the colour under "@theme".

If I were to do this again I would change the tree image in the middle to have transparency of it’s own instead of layering a coloured box over it to be able to see the text better and I would ensure that the gallery images scale to fit the page instead of being cropped.

The page can be found here: https://pdtrentham.github.io/Tailwind-CSS/ and then clicking "home"

<a href="Tailwind CSS Practical/home.html">Home</a> 
