# Sliceform Studio

My name is Yongquan Lu ("YQ" to most people) and I am a paper artist currently studying mathematics and computer science at MIT. Sliceform Studio (formerly Wallpaper) is a system I built with my advisor [Erik Demaine](http://erikdemaine.org) at [CSAIL](http://csail.mit.edu) to simplify the process of creating and designing sliceform paper artwork, an artform where long strips of paper are cut, folded, and slotted together to form geometric configurations.

The source code is available on [Github](http://github.com/yqlu/sliceformstudio).

### The Theory

For more information about the theory behind the application, please refer to [the 2015 Bridges Proceedings](http://archive.bridgesmathart.org/2015/bridges2015-367.html) or [the paper in the Journal of Symmetry](http://erikdemaine.org/papers/Sliceform_Symmetry/).

### Attributions

To the best of my knowledge, the techniques I am exploring were first developed by artists such as [Chris Palmer and Jeff Rutzky](https://www.youtube.com/watch?v=2TNUxWVgZTs), and have since been popularized by others such as [Christiane Bettens](https://www.flickr.com/photos/melisande-origami/sets/72157613125224450).

I owe the concept of the pattern editor to [Craig Kaplan](http://www.cgl.uwaterloo.ca/~csk/)'s work on [Taprats](http://www.cgl.uwaterloo.ca/~csk/washington/taprats).

### Running the app locally

Make sure you have [Node](nodejs.org) and [Bower](bower.io) installed.

First, install Harp with:

```
sudo npm install -g harp
```

Next, in the same directory as Wallpaper, fetch all the packages with:
```
bower install
```

Then, run:
```
harp server
```

The app should now be running on localhost:9000.

Note that it may not display correctly as the git repo excludes images and other binary assets.

### Contributions

Any pull requests on Github are welcome!

### Contact

If you wish to contact me, email at: yqlu -at- sliceformstudio.com.

### License

Distributed under the MIT License.
