# Proxy HTTP[S] over SSH

Sometimes you want to access a web resource from a different network than you're
currently on--perhaps you don't have a VPN to access work resources from home,
or perhaps you're traveling and want to see your home country's Amazon page.

## Usage

`proxy.sh <somehost>`

Configure a SOCKS proxy for all HTTP[S] traffic through `<somehost>`. All web
traffic will be automatically proxied. 

To disable the proxy, send SIGTERM by typing `ctrl-c` (don't simply kill the
terminal window).

