# Subcommission on Timescale Calibration Website
The small website for the Cambrian subcommission of the International Commission on Stratigraphy, online at <http://stratigraphy.org/subcommission-timescale-calibration/>. This is a temporary home and it will eventually be housed at <http://calibration.stratigraphy.org>.


## Content
Content for this website is managed by the [Timescale Calibration subcommission of the ICS](https://stratigraphy.org/subcommissions#calibration).

See Contacts below.


## Technical website operations
This is a [Jekyll](https://jekyllrb.com/) *static site generator* website which means the source files are pretty much simplified HTML pages - [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)-formatted text files - which you can see stored in the [pages/](pages/) folder. These are combined with a very simple template to add headers & footers to all pages and produce the final HTML web pages which are then delivered online with a web server. We are using the built in [GitHub Pages](https://pages.github.com/).

This subcommission's website is hosted within the ICS's set of code repositories, see <https://github.com/i-c-stratigraphy/subcommission-timescale-calibration>.

Setup:

`jekyll new . --force`

Running the site locally:

`bundle exec jekyll serve`

to fix dependencies for Ruby 3: `bundle update && bundle install` then `bundle add webrick`

## License & Rights
The content of this repository is licensed using the Creative Commons Attribution 4.0 license:

* <https://creativecommons.org/licenses/by/4.0/>

See the [local copy of the license deed](LICENSE) for details.

&copy; International Commission on Stratigraphy 2020, all rights reserved


## Support and contacts
*For website content:*  
**Bradley D. Cramer**  
Associate Professor  
Department of Earth & Environmental Sciences  
University of Iowa  
Iowa City, Iowa 52242, USA  
<bradley-cramer@uiowa.edu>  


*For website technical matters:*  
**Dr Nicholas Car**  
ICS Webmaster  
<nicholas.car@surroundaustralia.com>  
