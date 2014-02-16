# Clrs

Easily include the <www.clrs.cc> variables in your Rails apps.

## Installation

Add this line to your application's Gemfile:

    gem 'clrs'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install clrs

You will then need to require the stylesheet in your application.css:

```
*= require clrs;
```

## Usage

Now you have access to the following variables:

```scss
$navy:    #001f3f;
$blue:    #0074d9;
$aqua:    #7fdbff;
$teal:    #39cccc;
$olive:   #3d9970;
$green:   #2ecc40;
$lime:    #01ff70;
$yellow:  #ffdc00;
$orange:  #ff851b;
$red:     #ff4136;
$maroon:  #85144b;
$fuchsia: #f012be;
$purple:  #b10dc9;
$white:   #ffffff;
$silver:  #dddddd;
$gray:    #aaaaaa;
$black:   #111111;
```

__NOTE:__ You must require the clrs stylesheet before stylesheets using the above scss variables.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
