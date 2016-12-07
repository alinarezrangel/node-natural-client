# NodeNatural Client Application #

NodeNatural can be used from a web browser, but with this native client, you
can:

* Use *LeafNode*, the NodeNatural web browser.
* Use the *Fullscreen* button at the top.
* Open the NodeNatural server in your desktop with a simple click.

This client was made using [nwjs](http://nwjs.io)

## Contributors ##

* Alejandro Linarez Rangel

## Usage ##

```sh
nw .
```

## Source explained ##

nwjs enables to a frame to embed **any** other page and grant it NodeJS
permissions. The index file is a simple frame and LeafNode can embed another
pages in a secure form using `nwfakeTop` and others.

## Notes ##

This client assumes that the NodeNatural server is running on
<http://localhost:4567/>, change the value of the `src` attribute in the
[index.html](index.html) file to your target devices IP and port.

## License ##

See the [LICENSE](LICENSE) file.

