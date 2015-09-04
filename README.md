This provides a generic heartbeat mechanism for anything that needs to run in
multiple nodes (machines, or even just in multiple processes on one machine) and
nodes need to have a way to detect when other nodes have gone down, so that something
can be done about it.  That "something" is specified by the caller of this library.
