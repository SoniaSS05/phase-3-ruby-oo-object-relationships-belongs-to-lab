# Object Relationships: Belongs To Lab

## Learning Goals

* Write classes that are related via the "belongs to" relationship

## Instructions

In this lab, you'll be coding a `Song` and `Artist` class. A song should belong to an artist. You'll also be coding a `Post` and `Author` class. A post should belong to an author. 

* Artists should have a name. 
* Songs should have a title and belong to an artist. A song should be able to tell you the name of its artist:

```ruby
song.artist.name
  # => "Beyonce"
```

* Posts should have a title and belong to an author. A post should be able to tell you the name of its author:

```ruby
post.author.name
  # => "Hillary"
```
