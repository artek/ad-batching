# Ad Batching

Simple example of single request architecture with [Prebid.js](https://github.com/prebid/Prebid.js/) and [Google Publisher Tags](https://developers.google.com/publisher-tag/guides/get-started).

Ad batching packages multiple ad slots into a single bid request and single ad server request. It helps decrease ad load time and increase ad viewability when more than one ad is loading at the same time.

In this code I'm using ad units codes, sizes and placement ids found in code examples on [prebid](https://docs.prebid.org/dev-docs/examples/basic-example.html) and [gpt](https://developers.google.com/publisher-tag/samples) websites.
