# Responsive Design and Dataviz: Charts That Work Everywhere

A presentation by [Tyler Machado](http://www.tylermachado.com/) at [CASCADE BOS](http://www.meetup.com/cascadebos/) on June 28, 2016.

## The slides

[Here are the slides!](http://tylermachado.github.io/responsive-design-and-dataviz/#/) I don't know if they will make sense without me rambling next to them but that's okay!

## What we've done at HBR
- [How Corporate Boards Connect, in Charts](https://hbr.org/2016/04/how-corporate-boards-connect-in-charts), Harvard Business Review
	- went with a circle-based chart type to fit in squares, which work well on both landscape and portrait orientations
	- that single chart type meant only very minor styling changes were necessary for different screen sizes
	- custom chart type idea sketched out during meeting with editor, developer and designer
- [The Decline of Yahoo in Its Own Words](https://hbr.org/2016/06/the-decline-of-yahoo-in-its-own-words), Harvard Business Review
	- traditional line chart on large screens, vertical heatmap on small screens
	- two different chart types meant more coding work, though in this case we felt it was worth it because each chart is very successful in its context
	- charts are generated from the same Javascript file, and use the same data
	- Javascript function decides which chart to render based on window inner width, and that function is called every time the window loads or is resized

## Other examples
- [Where AirAsia Flight 8501 Was Lost and Debris Found](http://www.nytimes.com/interactive/2014/12/28/world/asia/airasia-flight-qz8501-map.html?_r=0), The New York Times
	- map crops and copy changes at smaller sizes
- [How earbuds can wreck your hearing (especially for young people)](http://www.chicagotribune.com/news/ct-earphones-could-be-hurting-your-ears-20160229-htmlstory.html), Chicago Tribune
	- radically different chart type at different screen sizes
	- some copy omitted at smaller sizes
- [2015 Women's World Cup Predictions](http://projects.fivethirtyeight.com/womens-world-cup/), FiveThirtyEight
	- different entry point on mobile; considers what information looks best when you first arrive on different devices
- [The Urban Neighborhood Wal-Mart: A Blessing Or A Curse?](http://www.npr.org/2015/04/01/396757476/the-neighborhood-wal-mart-a-blessing-or-a-curse), NPR
	- small multiples on large screens, animated GIFs on small screens