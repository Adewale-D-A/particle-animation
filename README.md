# Particle Animation

> This standalone react componenet uses canvas to create a mouse responsive particle animation via an image or text

> The image required will have to be converted in a base64 image url and replaced with the variant `imageString` and passed into the function. Text is more straight forward such that a any text can be passed into the function and it renders it as a particle.

> To enable entry animation in x and y coordinates, the constructor x, y in the `Particle` class needs an initial parameter value which has been commented out, a simple uncomment of the value there will give the user an idea of what the entry animation can do and its potential in giving the users a good experience while using the app

> During th initialization of the class Effect, the last parameter which is a boolean value determines if the particles is rendering an image base64 URL or a text.

> Calling the method `effect.wrapText` with the text intended to be display will suffice for Text particle animation

<a href="https://onlinepngtools.com/convert-png-to-base64" target="_blank">convert image into a base64 string here</a>
