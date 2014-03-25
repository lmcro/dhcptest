## dhcptest

This is a DHCP test tool. It can send DHCP discover packets, and listen for DHCP replies.

The tool is cross-platform, although you will need to compile it yourself for non-Windows platforms.

The tool is written in the [D Programming Language](http://dlang.org/).

## Download

You can download a compiled Windows executable from my website, [here](http://files.thecybershadow.net/dhcptest/).

## License

`dhcptest` is available under the [Boost Software License 1.0](http://www.boost.org/LICENSE_1_0.txt).

## Changelog

### dhcptest v0.2 (2014-03-25)

 * License under Boost Software License 1.0
 * Add documentation
 * Add `--help` switch
 * Add `--bind` switch to specify the interface to bind on
 * Print time values in human-readable form
 * Heuristically detect and print ASCII strings in unknown options
 * Add option names from RFC 2132
 * Add `help` and `quit` commands
 * Add MAC address option to `discover` command

### dhcptest v0.1 (2013-01-10)

 * Initial release
