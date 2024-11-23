This is mostly a rust learning project with a chance of being actually used.

The goal of this project is to build a mock-dns server that can be used in integration testing.

Desired features:
* handle all common record types including SRV
* support weighted records
* be configurable through file 
* be configurable through API calls
* [NICE to have] support for tests to define behavior for a special test or to verify that expected resolutions happened. Similar to java's mockito

At this moment in time there is no guarantee that this project will ever be completed.
    


The foundations are being built using the [guide provided by EmilHernvall](https://github.com/EmilHernvall/dnsguide)