# Install:

    pip install bcode


# Use:

    from bcode import bdecode
    print bdecode(open('foo.torrent').read())


# Documentation:

## bencode(input)

Encode python types to bencode format.


## bdecode(input)

Decode strings from bencode format to python value types.


Learn more about bencode and bittorrent at: http://wiki.theory.org/BitTorrentSpecification#bencoding


## Bugs & Co.

If you find bugs or new features that are not implemented you can:

 * [Fork and implement the changes](https://github.com/medecau/bcode/fork)
 * [Fork and write a test that fails but shouldn't](https://github.com/medecau/bcode/fork)
 * [Submit an issue in github](https://github.com/medecau/bcode/issues)
