## Changes between 1.0.0-rc2 and 1.0.0-rc3

No changes yet.


## Changes between 1.0.0-rc1 and 1.0.0-rc2

### Future results now can be dereferenced

Many Spyglass functions return futures. Starting with the 1.0.0-rc2 release, it is now possible to
deref (`@future`) them.


## Changes between 1.0.0-beta1 and 1.0.0-rc1

### Documentation guides

Spyglass now has [documentation guides at clojurememcached.info](http://clojurememcached.info).



## 1.0.0-beta1

Initial release

Supported features:

 * get, async get
 * multi-get (bulk get), async multi-get
 * delete
 * replace
 * flush
 * add, incr, decr (need to use custom transcoders because of the SpyMemcached idiosyncracies)
 * gets, CAS, async CAS
