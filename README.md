

<iframe src="typing-animation.html" frameborder="0" width="100%" height="200"></iframe>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        #letter-container {
            display: inline-block;
            margin-top: 50px;
            font-size: 24px;
        }
    </style>
</head>
<body>
    <div id="letter-container"></div>

    <script>
        const letterContainer = document.getElementById('letter-container');
        const phrases = [
            "This is the first phrase.",
            "Now we're typing the second phrase.",
            "And here's the third phrase!"
        ];
        let currentPhraseIndex = 0;
        let currentLetterIndex = 0;

        function typeLetter() {
            if (currentLetterIndex < phrases[currentPhraseIndex].length) {
                letterContainer.innerHTML += phrases[currentPhraseIndex].charAt(currentLetterIndex);
                currentLetterIndex++;
                setTimeout(typeLetter, 50); // Adjust typing speed here (in milliseconds)
            } else {
                setTimeout(eraseLetter, 1000); // Wait for a second before erasing
            }
        }

        function eraseLetter() {
            if (letterContainer.innerHTML.length > 0) {
                letterContainer.innerHTML = letterContainer.innerHTML.slice(0, -1);
                setTimeout(eraseLetter, 30); // Adjust erasing speed here (in milliseconds)
            } else {
                currentPhraseIndex = (currentPhraseIndex + 1) % phrases.length; // Cycle through phrases
                currentLetterIndex = 0;
                setTimeout(typeLetter, 500); // Wait for half a second before typing the next phrase
            }
        }

        // Start typing animation
        typeLetter();
    </script>
</body>
</html>





======================================================================================================================================

Future Web Developer
--------------------

Catchaaaaaaaa.

* 🧠  I'm learning Javascript

### Skills


<p align="left">
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="36" height="36" alt="JavaScript" /></a><a href="https://www.oracle.com/java/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/java-colored.svg" width="36" height="36" alt="Java" /></a><a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" width="36" height="36" alt="HTML5" /></a><a href="https://www.w3.org/TR/CSS/#css" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/css3-colored.svg" width="36" height="36" alt="CSS3" /></a>
</p>


### Socials

<p align="left"> <a href="https://www.github.com/jerick-navales" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" /> </picture> </a> <a href="http://www.instagram.com/jewick1" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="undefined" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram.svg" width="32" height="32" /> </picture> </a></p>

### Support Me

<ul style="list-style-type: none; margin: 0;">

<li style="display: inline-block; margin-right: 0.25rem;"><a href="https://www.buymeacoffee.com/Jerick Navales"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" width="150"/></a></li>

</ul>
