
[![GoDoc](http://godoc.org/github.com/tleyden/cb-heartbeat?status.png)](http://godoc.org/github.com/tleyden/cb-heartbeat) [![Build Status](https://drone.io/github.com/couchbase/cb-heartbeat/status.png)](https://drone.io/github.com/couchbase/cb-heartbeat/latest)

This provides a generic heartbeat mechanism for anything that needs to run in
multiple nodes (machines, or even just in multiple processes on one machine) and
nodes need to have a way to detect when other nodes have gone down, so that something
can be done about it.  That "something" is specified by the caller of this library.
