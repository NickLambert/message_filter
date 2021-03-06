# message_filter 

A size or time based message filter that takes any generic type as a key and will drop keys after a time period, or once size of container is reached (LRU Cache pattern). The filter has Add key method only, a delete function will be added at a later stage. This is a handy container for network based systems to filter previously seen messages.

|Crate|Travis|Appveyor|Coverage|
|:------:|:-------:|:-------:|:-------:|
|[![](http://meritbadge.herokuapp.com/message_filter)](https://crates.io/crates/message_filter)|[![Build Status](https://travis-ci.org/dirvine/message_filter.svg?branch=master)](https://travis-ci.org/dirvine/message_filter)|[![Build status](https://ci.appveyor.com/api/projects/status/u98ggp4mk4l76ic4/branch/master?svg=true)](https://ci.appveyor.com/project/dirvine/message-filter/branch/master)|[![Coverage Status](https://coveralls.io/repos/dirvine/message_filter/badge.svg)](https://coveralls.io/r/dirvine/message_filter)|

| [ API Documentation](http://dirvine.github.io/message_filter/) | [MaidSafe System Documention](http://systemdocs.maidsafe.net/) | [MaidSafe web site](http://www.maidsafe.net) | [Safe Community site](https://forum.safenetwork.io) |

#Todo
- [x] Implement add_key  (bool return, true added, false == already exists)
- [x] Test add_key (time and size based tests)
- [x] API version 0.1.0
