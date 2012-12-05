#FontCustom v0.1.2

**Generate custom icon webfonts from the comfort of the command line.**

[Full documentation](http://endtwist.github.com/fontcustom/)<br/>
[Feedback and issues](https://github.com/endtwist/fontcustom/issues) to the core app. 


##What is FontCustom.sass?
There are two difference between FontCustom and FontCustom.sass. The main difference is that I converted the [template files](http://goo.gl/GZ53q) from old vanilla CSS to Sass. Nothing really magical there.

The next difference is that I beat up on the [generator.rb](http://goo.gl/IGZi0) file so that this better suits the Toadstool framework. Specific placement of the generated font files and a generated Sass partial as well.

Oh yeah, this is a 1:off gem `gem install fontcustomtoadstool`. 

##Installation
```sh
# Requires FontForge
brew install fontforge eot-utils ttfautohint
gem install fontcustomtoadstool
```

##Usage
```sh
fontcustom compile path/to/vectors  # Compile icons and css to path/to/fontcustom/*
fontcustom watch path/to/vectors    # Watch for changes
```

##To-do
See [project issues](http://goo.gl/RfCKl) for an updated list.