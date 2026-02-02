# Janus "Hello World" Plugin

This is an updated version a [Hello World plugin](https://github.com/mqp/janus-helloworld-plugin) by Marshall Polaris. This version builds successfully against the latest version of the [Janus WebRTC Server](https://github.com/meetecho/janus-gateway). It also uses CMake instead of automake.

## Building

* Build and install Janus Gateway as described at https://github.com/meetecho/janus-gateway#compile
* `git clone https://github.com/megafarad/janus-helloworld-plugin.git`
* `mkdir -p ./janus-helloworld-plugin-build`
* `cd ./janus-helloworld-plugin-build && cmake ../janus-helloworld-plugin && make && make install`

## License

MPL-2.0