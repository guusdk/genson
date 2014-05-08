[![Build Status](https://travis-ci.org/owlike/genson.svg?branch=master)](https://travis-ci.org/owlike/genson)

Genson json <-> java conversion library.

Project url : http://code.google.com/p/genson/
Issues tracking url : http://code.google.com/p/genson/issues/list

*** Basic usage ***
// serialize
Genson genson = new Genson();
String json = genson.serialize(new int[1,2,3]);
// json value is "[1,2,3]"

// deserialize
int[] arrayOfInt = genson.deserialize(json, int[].class);

for advanced usage have a look at the wiki or javadoc.