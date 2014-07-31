---
layout: post
title: Franklin Finds a Froom update v1.1
---

I posted an update for Franklin Finds a Froom earlier this morning to the Google Play store.

The biggest change that comes with v1.1 is that a level won't completely restart after you die. I don't remember why I decided not to do it that way in the first place. But the three games I play the most on the workplace's arcade machine (Ms. Pac-Man, Burger Time, and Galaga 3) don't throw away all the progress you've made in a level when you die, so why should I? Actually, come to think of it, Galaga 3 might. Maybe it was a way that I thought would make the game frustratingly hard that some people come to enjoy. But in the end I think it was just more frustrating or annoying than anything else. Hopefully this little bit will help players get just a few more levels beyond where they've been stuck at.

Some other smaller changes to note:
- Now that a level still progresses after you die, I needed to handle cases where the player is spawned right into the path of an oncoming Froom. Instead of insta-dying, a brief period of a immunity is given so players have a chance to move safely out of the way.  
![Player immunity]({{ site.baseurl }}/images/franklin-finds-a-froom/v1.1-immunity.png)  
- The volume of the background music has been decreased a touch. It may have been a tad loud.  
- This is barely noticeable, but the Android launcher icons have also been updated. I used this tool (http://romannurik.github.io/AndroidAssetStudio/icons-launcher.html) instead of just chopping the head off of one of Franklin's sprites.  
- There's a small UI pause button added to the top of the screen. This was really just done in preparation for a potential port over to iOS. But unless someone wants to give me $99 for the dev fee, it's probably not gonna happen.  
![Pause button]({{ site.baseurl }}/images/franklin-finds-a-froom/v1.1-pause-button.png)  
- And then some other bug fixes that may also not be terribly noticeable.  

Thanks are in order for friends, coworkers, and Vallar on [TIGSource](http://forums.tigsource.com/index.php?topic=42091.0) who all gave really valuable feedback that led to the changes made.

If you haven't yet, you can get Franklin Finds a Froom [HERE](https://play.google.com/store/apps/details?id=com.jonuy.franklinfroom).