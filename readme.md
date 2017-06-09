# Couchbase Preview - Beer City Code @ Grand Rapids, MI


## Basics

Couchbase stores documents (JSON) in Couchbase Server (blobs in SQLite under the hood) by key-value pairs.

Couchbase Lite (client) connects with Sync Gateway to manage the current state of through document changelists.

Channels specify permission control for documents. ( '!' is the public channel)


## Useful links:

### [Resolving Conflicts](https://developer.couchbase.com/documentation/mobile/current/guides/sync-gateway/resolving-conflicts/index.html)

If conflicts arise between changelist documents, the pending conflicts will remain until the conflicts resolve. This can result in a growing DB which needs trimming.

### [OpenID Connect](https://developer.couchbase.com/documentation/mobile/current/guides/authentication/openid/index.html)

Nifty

### [Performance](https://www.slideshare.net/renatko/couchbase-performance-benchmarking)

Couchbase appears to have better performance compared to Cassandra and MongoDB.

## Other

`sync_gateway {{yourJsonConfig.JSON}}` to run Sync Gateway

`localhost:4985/_admin/` for admin view.

