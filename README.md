ffprobe-static
====
_Note: fork of [joshwnj](https://github.com/joshwnj) for the purpose of providing temporary arm64 support._
___

Static binaries for `ffprobe`.

Based on <https://github.com/eugeneware/ffmpeg-static>.

Binaries are from <http://ffmpeg.zeranoe.com/builds/>

Usage
----

```js
var ffprobe = require('ffprobe-static');
console.log(ffprobe.path);
```

Binaries
----

* [ARM (Apple Silicon) Mac OSX](https://osxexperts.net/)
* [64 bit Mac OSX](https://evermeet.cx/ffmpeg/)
* [64 bit Linux](http://johnvansickle.com/ffmpeg/)
* [32 bit Linux](http://johnvansickle.com/ffmpeg/)
* [64 bit Windows](http://ffmpeg.zeranoe.com/builds/win64/static/)
* [32 bit Windows](http://ffmpeg.zeranoe.com/builds/win32/static/)

Acknowledgements
----

Special thanks to [joshwnj](https://github.com/joshwnj) for <https://github.com/joshwnj/ffprobe-static>, which this is based upon.
