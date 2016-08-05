# Bootstrap Social Buttons
Common social media buttons for Bootstrap 4

![Buttons](./img/buttons_8.5.16.png "Available Buttons")

## Implementation

This file is meant to be used with Bootstrap 4 Sass source code. To begin, add the partial Scss file `_social-buttons.scss` to the Bootstrap folder `scss`, this will likely be in the `vendor/twbs/bootstrap` folder if you are using Composer.

Then, modify the file `bootstrap.scss` to import the social buttons on the line after it imports normal buttons:
``` sass
@import 'buttons';
@import 'social-buttons';
```

Then use the compiler of your choice to recompile the Bootstrap Scss down to CSS and you're good to go!

## Usage

to get normal buttons:
``` html
<button type="button" class="btn btn-social-facebook">Facebook</button>
<button type="button" class="btn btn-social-twitter">Twitter</button>
```

to get outlined buttons:
``` html
<button type="button" class="btn btn-outline-social-instagram">Instagram</button>
<button type="button" class="btn btn-outline-social-googleplus">Google</button>
```
