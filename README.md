## firefoxos-haml-sass-boilerplate

This is a [boilerplate](http://en.wikipedia.org/wiki/Boilerplate_%28text%29) for FirefoxOS web applications where you write 
[haml](http://haml.info/) and [sass](http://sass-lang.com/) code.

It's easier to maintain haml and sass code and it's definitely more fun to write it. This boilerplate is for [rubyists](http://en.wiktionary.org/wiki/Rubyist)
but it doesn't require deep knowledge of Ruby. I'm pretty sure anyone can use this easily, and I guarantee that web can be fun again :)

I've integrate [FirefoxOS Building Blocks](http://buildingfirefoxos.com/) in the public folder. You can link to desired stylesheets following my example
from ```index.html.haml``` from the ```head``` section.

### How to use?
You just clone this repository and start writing code.
```git clone https://github.com/radubogdan/firefoxos-haml-sass-boilerplate.git```

Don't forget to ```cd firefoxos-haml-sass-boilderplate``` and run ```bundle install```.

Then you have to start [Guard](https://github.com/guard/guard).
```bundle exec guard```

Open the index page ```vim index.html.haml``` and every time you save that file, guard will compile it in public/index.html if you don't have errors. Guard will also compile sass/scss and coffescript (to use coffescript you have to change some stuff in Guardfile - contact me if you don't know.)

To visualize the result in a browser, you can open a python server in the public folder: ```python -m SimpleHTTPServer``` and connect to ```http://0.0.0.0:8000/```.

### License
[MIT](https://github.com/radubogdan/firefoxos-haml-sass-boilerplate/blob/master/LICENSE)

To contribute to this, [fork](https://github.com/radubogdan/firefoxos-haml-sass-boilerplate/fork) this repository and pull request.
For any other questions please contact me on email.

For complaints forward the messages to /dev/null
