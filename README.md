CouchDB-Lucene Docker Image
===========================

Not for public use (yet).

Contains Java8

CouchDB-Lucene 2.1

Based on Alpine 3.5 Linux to keep the footprint small as possible.


Build
-----

`sudo docker build -t benjamingrogg/alpine-couch .`

Run
---

`sudo docker run -ti -d -p5985:5985 benjamingrogg/alpine-couch /opt/couchdb-lucene-2.1.0-SNAPSHOT/bin/run`

