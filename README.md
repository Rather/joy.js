# joy.js [![Build Status](https://secure.travis-ci.org/joyjs/joy.js.png)](http://travis-ci.org/joyjs/joy.js)

A Joyful 2D HTML5 Game Engine, designed to be easy to use.

Current version: 0.1.1 ([CHANGELOG](CHANGELOG.md))

## Features

  - Keyboard input
  - Mouse input
  - Viewport / Head-up display
  - Tilemap / Tileset
  - Reusable object behaviours
  - Collision detection
  - Scene graph
  - Audio (provided by [howler.js](https://github.com/goldfire/howler.js))
  - Tweens (provided by [tween.js](https://github.com/sole/tween.js))
  - Device feature detection
  - Custom preloader

## Resources

  - [Examples](http://joyjs.org)
  - [API](http://joyjs.org/api/)
  - [Google Group](https://groups.google.com/forum/#!forum/joyjs)
  - Follow [@joyjs_](https://twitter.com/joyjs_) on twitter for updates

## TODO (enchancements / features)

  - Touch events
  - Normalized `collidePosition` on DisplayObject / RectCollider calls.
  - Handle custom WebFonts on loader pipeline. (lib/base/font.js)
  - Physics integration. (lib/core/behaviour/physics.js)


## Contributing

We use [npm](https://npmjs.org) modules, such as [grunt](https://github.com/gruntjs/grunt) and
[qunit](https://github.com/gruntjs/grunt-contrib-qunit)  during development process.
If you're under Windows platform, please take a look at
[this](https://gist.github.com/2489540) guide to setup your environment.

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## License

Please see LICENSE file.
