daemons-cc
===

daemons-cc is the FreeBSD's congestion control implementation extracted as a userspace library.

At the moment, NewReno and Cubic have been ported.
Since the changes to the modular API is kept minimum, it is anticipated that other algorithms can be ported fairly easily.

Goals
---
* create a congestion control implementation that can be used for QUIC
* retain the modular API provided by mod_cc
