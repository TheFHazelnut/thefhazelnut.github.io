---
title: "To Hell And Back"
header:
    image: /images/Beholder1921.png
    teaser: /images/GoodDog.jpg
sidebar:
    - title: "Role"
    - image: http://placehold.it/350x250
    - image_alt: "logo"
    - text: "Designer, Programmer, Artist"
gallery:
    - url: /images/MainMenu.png
      image_path: /images/MainMenu.png
      alt: "image 1"
    - url: /images/MainMenu.png
      image_path: /images/MainMenu.png
      alt: "image 2"
    - url: /images/MainMenu.png
      image_path: /images/MainMenu.png
      alt: "image 3"

---

To Hell and Back is a 2D top down roguelike wave based shooter (a mouthful) about a knight fending off hordes and hordes of demons. This game was directly inspired by the likes of Risk of Rain and Vampire Survivors. The player receives various items at the end of waves and after killing bosses that give them some unique benefit. Stacks of different items will further empower their effects, which will be needed to fight enemies that get increasingly tough as the game goes on.

{% include gallery caption ="Isn't it great" %}

This was a game that I worked on for a semseter of class as a solo dev. I created all the art, did all the programming, and also designed the entire game. The outside assets used were for all the various sound effects in the game. Making this game was a real test of how well I could make a modular system for both the entities and the items, since there were so many items with vastly differing effects. I ended up using a lot of inheritance and careful GameObject placement to make the system work, and in the end, I'm very proud of what I was able to make here. The codebase could still be improved, but for the most part, works really well, as I could even now go back and add more items relatively quickly and easily without having to scour the entire codebase. Coding singular and stacking functionality is easily implementable, and new enemy types can also be added pretty simply. I consider this my magnum opus as of right now I guess, and it was so much fun to make. 

### <a href="https://github.com/julianjriley/ToHellAndBack"> Github Page </a>