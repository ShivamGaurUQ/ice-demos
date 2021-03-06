This directory contains an Android Studio project for the multicast talk
app.

The app allows Android devices to discover one another via [multicast][1] and
then establish a secure peer-to-peer connection. Multicast discovery
messages are only sent when users are in the "Connect" dialog. WiFi must
be enabled in all devices.

This app demonstrates several useful techniques that are instructive for
Android developers:

 * Issuing [asynchronous Ice invocations][2] to maintain a responsive user
   interface
 * Using [bidirectional connections][3] to receive "push notifications" from
   a remote peer
 * Proper separation of UI and application logic

Refer to the [java-compat README.md](../../README.md) for build instructions.

[1]: https://doc.zeroc.com/display/Ice37/Datagram+Invocations
[2]: https://doc.zeroc.com/display/Ice37/Asynchronous+Method+Invocation+%28AMI%29+in+Java+Compat
[3]: https://doc.zeroc.com/display/Ice37/Bidirectional+Connections
