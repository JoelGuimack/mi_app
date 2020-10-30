![](https://github.com/JoelGuimack/mi_app/workflows/Ruby/badge.svg)

para ver el reporte de analisis de codigo:

https://JoelGuimack.github.io/mi_app/overview.html#



### Para el setup sin docker:

install ruby 2.6.5

Setup:
	sudo apt-get install phantomjs

on the project root:
	gem install bundler
	bundle install

to run app:
	ruby app.rb

for unit test:
	rspec

for acceptance test:
	cucumber