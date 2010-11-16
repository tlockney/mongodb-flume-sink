# MongoDB Flume Sink

This is a very rough sketch of the beginnings of a Flume sink for MongoDB. I honestly haven't even tried running this yet, so YMMV (big time).

### Building it

The work needed to build a Flume plugin is a bit awkward at the moment. First, you'll need to check out the Flume source itself from Github (https://github.com/cloudera/flume/). Once you have that, drop this into flume/plugins and then run 'ant' to build. 

For now, don't bother asking me any questions -- I'll add more details and update this readme after I've actually verified that this thing even attempts to work.
