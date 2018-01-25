# step 1 drawing a square
- new Path.Circle(new Point(100, 100), 10).fillColor = 'yellow';
# step 2 finding max height and width of page
- view.size.height, view.size.width
# step 3 able to change color of circle 
- function onFrame(event) {
            animateCircle.fillColor.hue += 1;
        }
# step 4 scale down each frame
- animateCircle.scale(.9);