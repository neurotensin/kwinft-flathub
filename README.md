# kwinft-flathub
an attempt to build kwinft in flathub for non ARCH systems.

a) There are dependences in shared-modules/*.json
b) everything builds using a compbination of versions and make systems
c) some things are not found e. QtQuick Components, but are runtime dependent (so flatpak should provide)
d) kwinft is version 5.24.0 and failed to build due to a C++ error that is not resolvable.
