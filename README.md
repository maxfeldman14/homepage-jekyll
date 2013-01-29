#maxfeldman.net

To use, you must have Ruby and gem installed

You can install the required gems with these commands: (You may need root access)
```
  gem install haml
  gem install rake
  gem install jekyll
```

To run, you can either
```
  rake build
```
to build into a folder (which works, but may hang? and require CTRL-C), or
```
  rake preview
```
to build and start a web server listening on port 4000, that you access in a 
browser at [localhost:4000](http://localhost:4000).

Borrows heavily from [brandonwang.net](http://brandonwang.net). Also uses Twitter [Bootstrap](http://twitter.github.com/bootstrap/) and [Jekyll Bootstrap](http://jekyllbootstrap.com/).

##TODO
* Finish styling on (blog) posts, projects
* Re-add rake tasks for creating posts, projects
* Deal with weird horizontal overflow/width
