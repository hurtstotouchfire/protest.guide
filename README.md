## Contents

- [About this site](#about-this-site)
- [About Jekyll](#about-jekyll)
- [How to install/run](#how-to-installrun)
- [License](#license)

## About this site
This site is a one-page protest security guide. It is intended to be extremely light, fast-loading, mobile-friendly, and accessible. It is a work in progress. Please feel free to fork / contribute / log issues.

#### Notes:
- We pulled content from [here](http://www.urban75.org/mayday/safety.html) but ideally, content would be customized for a specific protest.
- ALL content on one single page.
- CSS needs more tweaking.
- Site must not use any javascript.
- Site must be accessible to screen readers.
- *Idea:* Provide a "download" link that will save this info to disk in case of cell signal blocking / tower overload.
- *Idea:* Add a section that's a kind of timestamped newsfeed.  Perhaps the "newsfeed" can go on a second page.
- *Idea:* SMS updates for newsfeed instead?

#### Todos:
- Minify / uglify CSS
- Audit for WCAG 2.1 AAA and log issues
- Lint all html and CSS files

## About jekyll

[Jekyll](http://jekyllrb.com/) is a static site generator, an open-source tool for creating simple yet powerful websites of all shapes and sizes. This site's theme was based off of [Harmony](https://github.com/gayanvirajith/harmony/), but we've removed all JS and will be continuing to pare down the payload as much as we can.

## How to install/run

1. Fork this repository.
2. Clone it: git clone https://github.com/YOUR-USERNAME/protest.guide.
3. If you're completely new to jekyll, please read more about [Jekyll](http://jekyllrb.com/) and [Github pages](https://help.github.com/articles/using-jekyll-with-pages).
4. Change your directory into cloned repository. 
5. Run `bundle install`
6. Edit the _config.yml on root directory. Change `url` property to to 
`http://127.0.0.1:4000` since you are going to run on localhost.
![url,baseurl,posts](https://actsecure.github.io/protest.guide/assets/images/what-is-a-baseurl.jpg "Base Url")
7. Run the jekyll server by having: `jekyll serve --baseurl ''` or `rake preview`   

Point your browser to [http://localhost:4000](http://localhost:4000).

Note: If you are a windows user please refer to this nice website - http://jekyll-windows.juthilo.com/ by Julian Thilo to configure ruby + jekyll on windows.

## License

Free / Open sourced under the 
[MIT](https://github.com/actsecure/protest.guide/blob/master/LICENSE.md).
