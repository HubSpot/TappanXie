# TappanXie

Want to use the [pure Java implementation](https://github.com/dain/snappy) of Snappy but have existing code and 3rd party
libraries using [xerial/snappy-java](https://github.com/xerial/snappy-java)? TappanXie is a bridge library that makes this sort
of migration easy. The TappanXie Bridge adds dummy implementations of all the xerial/snappy classes that just delegate to the
pure Java classes, making it a drop-in replacement.
