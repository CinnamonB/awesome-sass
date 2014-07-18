Awesome-Sass
============
A starter theme that incorporates Underscores Theme, Twitter Bootstrap's SASS, and Font-Awesome's SASS with Wordpress. This is not meant to utilize as a Parent Theme, but to hack it and make an awesome custom theme for Wordpress. Happy Coding!

Getting Started
---------------
#### Simple:

Go to Automattic's website http://underscores.me and generate the _s based theme from there. Input the desired name for your theme, as well as click the "Advance Options" if you want to add more custom information. Click the "Generate" button, and you're set with the base starter theme.

#### Manually

Download Awesome-Sass from GitHub. Begin by copying the _s directory and change the name to whatever your heart desires (for example, sassinista), then follow these five steps of Find and Replace on the name in all the templates.

1. Search for `'_s'` (inside single quotations) to capture the text domain.
2. Search for `_s_` to capture all the function names.
3. Search for `Text Domain: _s` in style.css.
4. Search for ` _s` (with a space before it) to capture DocBlocks.
5. Search for `_s-` to capture prefixed handles.

OR

* Search for: `'_s` and replace with: `'sassinista'
* Search for: `_s_` and replace with: `sassinista_`
* Search for: `Text Domain: _s` and replace with: `Text Domain: sassinista` in style.css
* Search for: ` _s` and replace with: Sassinista
* Search for: `_s-` and replace with: sassinista-

Then, update the stylesheet header in `style.css` and links in `footer.php` with your information. The other directories/files may remain untouched, unless you prefer to tweak it to your preference.

Once you've completed all steps, update or delete this readme.

Credits
-------
Without the following amazing creators, it would not have been possible to create an Awesome Sass Base Theme.
- [Automattic Underscores Starter Theme](https://github.com/automattic/_s)
- [Twitter Bootstrap SASS](https://github.com/twbs/bootstrap-sass)
- [Font-Awesome SASS](http://github.com/FortAwesome/Font-Awesome)

License
-------
This is for public use, use however it will benefit you.
[GNU General Public License v3 (or later)](http://www.gnu.org/licenses/gpl-3.0-standalone.html)