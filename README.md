# srv

Zoom, Teams, and other modern calling chats have complicated GUIs and are slow due to their complexity. Simplify your life with SRV (StarRust Video), our lightweight terminal-based app that brings video calls to even the sysadmin with nothing more than a terminal.

## Functionality
* Users can scan their local network for other available users listening on the same protocol and connect to them.
* Users can send and receive text messages from other users across networks.
* Users can voice call other users across networks.
* Users can video call other users across networks.

(Note: When we say network, we mean any network, be it LANs, over the internet etc. In principle, there is no difference as we are using standard TCP/UDP segments under the hood. However, most proof-of-concept functionality will be done over a local network.)
