!SLIDE
# Redis

Joseph Hsu

@jhsu

!SLIDE
## Redis.io

> Redis is an open source, advanced key-value store.
> It is often referred to as a data structure server
> since keys can contain strings, hashes, lists, sets and sorted sets.


!SLIDE
## Try it Out

[try.redis-db.com](http://try.redis-db.com/ ) or try it right in the docs

!SLIDE
# Types

!SLIDE
* string
* hash
* list
* set
* sorted set

!SLIDE
## GET / SET

    > GET hi
    (nil)
    > SET hi "hello, world!"
    OK
    > GET hi
    "hello, world!"

!SLIDE
## KEYS

    > KEYS hi*
    1) "hi"
    1) "hide"

!SLIDE
* lpop - remove the first entry in a list
* rpush - append to a list

useful for queueing
