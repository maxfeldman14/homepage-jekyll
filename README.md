#maxfeldman.net

To use, you must have Ruby and gem installed

You can install the required gems with these commands: (You may need root access)
```
  gem install haml
  gem install sass
  gem install rake
  gem install jekyll
```

To run, you can either
```
  rake build
```
to build into a folder, or
```
  rake preview
```
to build and start a web server listening on port 4000, that you access in a 
browser at [localhost:4000](localhost:4000)

Borrows heavily from [brandonwang.net](http://brandonwang.net). Also uses Twitter [Bootstrap](http://twitter.github.com/bootstrap/) and [Jekyll Bootstrap](http://jekyllbootstrap.com/).
