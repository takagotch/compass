### compass scss rb
http://compass-style.org/

https://github.com/Compass

#### compass-rails
https://github.com/Compass/compass-rails

```
gem 'sass-rails'
gem 'compass-rails'

bundle

# application.css
@import "compass";
@import "your_project/mixins";
@import "your_project/base";
/*
 *= require styleguide_full_of_compass_stuff
*/

# Gemfile
gem 'compass-rails'
gem 'susy'
bundle
bundle exec compass install susy

config.compas.require "susy"


```


```

```

