## step 1 drawing a square
- new Path.Circle(new Point(100, 100), 10).fillColor = 'yellow';
## step 2 finding max height and width of page
- view.size.height, view.size.width
## step 3 able to change color of circle 
- function onFrame(event) {
            animateCircle.fillColor.hue += 1;
        }
## step 4 scale down each frame
- animateCircle.scale(.9);
## step 5 get little circles to change colors
- Make those circles into a variable ::: var lilCircles = new Path.Circle(new Point(point), 20);
    - Then change thier color, because before it was only pushing in the color yellow: :: lilCircles.fillColor = 'yellow';
    - Push the little circles into an array ::: circles.push(lilCircles);

- allow circles to decrease in scale like the animateCircle did and delete the animateCircle 
## step 6 add in howler.js and play a sound onkeypress.
var sound = new Howl({
        src: ['sounds/bubbles.mp3']
      });
# differenct shapes
### With circles
![Alt text](http://g.recordit.co/GvW15betvn.gif)
### With squares
![Alt text](http://g.recordit.co/Ya8qdPqDEN.gif)
### With rotating squares
![Alt text](http://g.recordit.co/Adbp2mcyCF.gif)