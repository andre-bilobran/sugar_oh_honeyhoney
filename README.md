# sugar_oh_honeyhoney

As a  way to practice web crawling I pull some data out of https://fdc.nal.usda.gov/index.html using their API.
The code asks for input from the user (name of food, for example, tomato, banana, strawberry, cabbage, etc.) and give back the sugar content.
Its not the total carbohydrates, but the free sugar in that food (Monosaccharides which contain one sugar unit such as glucose, galactose, fructose, etc.)
Then, it stores the name of the food searched and its sugar content in a sqlite file.

That's it. Very simple. Just for fun.
