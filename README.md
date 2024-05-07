# thrice_fan_site
## __Unofficial__
A Thrice fan site, built for my web development class.

*Thrice are an American post-hardcore band from Irving California*

**I have been obsessed with them since I was 15**
They consist of:
- Dustin Kensrue on rhythm guitar and lead vocals
- Teppei Teranishi on lead guitar, synths, and other instruments
- Riley Breckenridge on Drums and programming synths
- Eddie Breckenridge on bass and backing vocals

Their official website is at [www.thrice.net](https://thrice.net), this is a fanmade effort.



![Thrice](pictures/thrice.jpg)

How I got the slideshow working: 
First, I got a handle and all the other stuff needed to reference these things. For more info, check out scripts.js
`setInterval( () => {
      slides[index].classList.remove('active');
      
      //Go over each slide incrementing the index
      index++;
      
      // If you go over all slides, restart the index to show the first slide and start again
      if (index === slides.length) index = 0; 
      
      slides[index].classList.add('active');

    }, time);`
