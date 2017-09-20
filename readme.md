# Izzie (Beta)

Izzie is an Nginx server script for independent publishing. We use it in production for https://indizr.com, so we're sharing it with the community as well for futher feedback, improvement, etc.

### Features
- Handles page requests via HTTPS for greater security.
- Compatible with PHP-based content management systems. (We use it  with WordPress 4.8.1, but it should work with Drupal and other PHP systems as well.)

### System Requirements
- Nginx v1.10.3 or later
- MySQL v14.14 or later
- PHP 7.0 or later
- A valid SSL cert (We recommend a free one from https://letsencrypt.org)

We also recommend running Izzie on an Ubuntu 16.04 machine or similar Linux box. But it should do fine on other Unix-like systems as well.

Izzie is, and always will be, free to use under MIT license. It is under active development, so we welcome feedback, pull requests, bug reports, etc. via https://github.com/indizr/izzie/

Peter A. McKay    
Founder   
Indizr    
<a href="https://twitter.com/peteramckay">@peteramckay</a>		
