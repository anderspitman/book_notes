# 2015-05-18 Mo

## Ch 5


### pg 76

* "Getting it working" is not the most important thing. The functionality of
  the code will probably change many times from the original intent, but the
  readability will always be important.

### pg 77

* Newpaper analogy. Most important information should be summarized at the
  beginning of a file, with more and more detail as you go down. Callees
  should be below callers, in the order they are used, unless multiple callees
  are cloesly related to each other.

## Ch 6

### pg 94

* Hiding implementation is more than just wrapping private variables in
  public functions, it is about abstraction, and distilling the interface down
  to the essence of the data.

### pg 95

* Data structures vs objects. Data structures hold data with "dumb" functions
  to access the data. Objects abstract. When you add a new type in a
  precedural system, all the of the functions must be updated, but none of
  the other types are affected. With objects, if you add a new type, none
  of the methods have to be updated, but if you add a new method to the
  common interface, all of the types must be updated.
