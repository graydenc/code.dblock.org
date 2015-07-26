---
layout: post
title: "Getting Things Done with Mongoid 5"
date: 2015-07-24
tags: [mongodb, mongoid, ruby]
comments: true
---
![mongoid]({{ site.url }}/images/posts/2015/2015-07-24-getting-things-done-with-mongoid-5/mongoid.jpg)

Mongoid 5 is now in Beta. For the upcoming 5.0.0 release, the repository is being moved to the MongoDB organization and is now fully supported by MongoDB, the company. Great!

Now begins the process of upgrading gems to Mongoid 5. I maintain half a dozen of these, so I am going to keep an up-to-date list of the gems that support the new version, which will incidentally help everyone find their favorite Mongoid gems to stay productive, much like [my 2011 post](/2011/05/27/ror-win-getting-things-done-with-mongodb-mongoid.html) did. So far I have added Mongoid 5 suport to two, and it was fairly easy.

### Supports Mongoid 5 Beta

- [Mongoid::Scroll](https://github.com/dblock/mongoid-scroll): Extension that enables infinite scrolling. [@d398c4e9](https://github.com/dblock/mongoid-scroll/commit/d398c4e9ce8279d4659dc26f18f3a77ef38decdb)
- [Mongoid::TagCollectible](https://github.com/dblock/mongoid-tag-collectible): Easily maintain a collection of Tag instances with aggregate counts from your model's tags. [@5813b77f](https://github.com/dblock/mongoid-tag-collectible/commit/5813b77f3981c5725f8253ff8b6df09e816f099b)

### Does Not Support Mongoid 5 Beta

This is your opportunity to help! Please contribute.

- [Mongoid::CollectionSnapshot](https://github.com/aaw/mongoid_collection_snapshot): Easy maintenence of collections of processed data.
- [Mongoid::Locker](https://github.com/afeld/mongoid-locker): Document-level locking.
- [Mongoid::CachedJson](https://github.com/dblock/mongoid-cached-json): Effective caching for nested JSON models.
- [Mongoid::Shell](https://github.com/dblock/mongoid-shell): Derive shell commands from Mongoid sessions and configuration options.
- [Mongoid::Slug](https://github.com/papercavalier/mongoid-slug): Adds a URL-like field to a model.
- [Mongoid::History](https://github.com/aq1018/mongoid-history): Creates an audit trail for all changes in a model.
- [Mongoid::Tracking](https://github.com/twoixter/trackoid): Tracker for document changes, more suitable when you need to embed tracking logic such as increments.
- [Mongoid::Taggable](https://github.com/wilkerlucio/mongoid_taggable): Adds tags to documents and make documents searchable by all or some tags.
- [Mongoid::TaggableWithContext](https://github.com/aq1018/mongoid_taggable_with_context): Adds tagging support with pre-aggregation.
- [Mongoid::Fulltext](https://github.com/aaw/mongoid_fulltext): An n-gram based full text search.
- [Mongoid::Search](https://github.com/mauriciozaffari/mongoid_search): Keyword-based search.
- [Mongoid::Geo](https://github.com/kristianmandrup/mongoid-geo): Geo-based searched.
- [Mongoid::Il8n](https://github.com/Papipo/mongoid_i18n): Localizable fields.
- [Mongoid::Votable](https://github.com/vinova/voteable_mongo): Vote models up/down.
- [Mongoid::Tree](https://github.com/ticktricktrack/mongoid_tree): Model tree structures.
- [Mongoid::Orderable](https://github.com/pyromaniac/mongoid_orderable): Ordered list implementation.
- [Mongoid::Atomic](https://github.com/jcoene/mongoid_atomic): Atomic updates support.
- [Delayed::Backend::Mongoid](https://github.com/collectiveidea/delayed_job_mongoid): Mongoid backend for DelayedJob.
- [Delayed::ShallowMongoid](https://github.com/joeyAghion/delayed_job_shallow_mongoid): Short-circuits serialization of Mongoid model instances when a delayed job is called on them.
- [CarrierWave::Mongoid](https://github.com/carrierwaveuploader/carrierwave-mongoid): Mongoid and MongoDB's GridFS support in CarrierWave.

### Missing a Useful Gem?

Please comment below or [make a PR](https://github.com/dblock/code.dblock.org) and update this post.