# SUSS website

This is the repository for the Sydney Univeristy Speleological Society(SUSS).

## Build status

![Build and deploy to ASF server](https://github.com/rafidmorshedi/suss-website-redesign/actions/workflows/push-to-asf.yml/badge.svg)

## Documentation TO DO
- How travis CI works
- The structure of the website
- how to mainitain the website

## Updating the Trip List
- The trip list is a Markdown table in the [triplist.md](./pages/triplist.md) file
- Changes to this file will update the triplist page.
- Details about Markdown syntax [here](https://www.markdownguide.org/extended-syntax/).

## Build / Maintenance instructions
- [Clone this repo](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
- Use Ruby v2.5.1 (via [rbenv](https://github.com/rbenv/rbenv) and [ruby-build](https://github.com/rbenv/ruby-build#readme))
  - Then `rbenv install 2.5.1 && rbenv global 2.5.1`
  - Note: These specific versions are important.
- Install `bundler v1.16.1` via `gem install`
- Run `bundle install` to install dependencies
- Run `bundler exec jekyll serve` to view the website locally at `http://localhost:4000`.
- Make any changes to the files and watch them update live.
- Once happy with your changes, commit your changes to Github.

The website is published using a Github [Action](https://github.com/rafidmorshedi/suss-website-redesign/actions). The Github Pages deployment is no longer in use.

## Website Structure
- Files within the "_posts" folder will become pages of their own.
  - For example, the `about` folder has a file called `2018-12-20-committee.html`.
  - The date will be removed, and the link to the page will be `/about/committee`.
  - Renaming the file to `2018-12-20-team.html` will move the page to `/about/team`. 
  - The date is compulsory, but will be ignored. The format must be **exactly** `YYYY-MM-DD-your-title-here.md` or `.html`

- Files within the "pages" folder also become pages of their own, but you can control their link with more power.
  - See any of the existing pages for examples.

- The "_data" folder contains lots of data to dynamically update information across the website.
  - For example, changes to the [publications.yml](./_data/publications.yml) file automatically update the entries on the [publications page](https://suss.caves.org.au/about/publications/).
  - `navigation.yml` controls the navigation bar at the top of the website.
  

<hr>

# Newsletter: Stay in Touch for Future Updates

If you are a webdesigner interested in Jekyll, the static website generator, this little newsletter is for you. I share tutorials, clever code snippets and information about my own Jekyll Themes called [*Feeling Responsive*][7] and [*Simplicity*][8]. Please don't expect weekly emails :)

[![Subscribe to Jekyll Newsletter](https://phlow.github.io/static/tinyletter_subscribe_button.png)](https://tinyletter.com/feeling-responsive)


[![Start Video](https://github.com/Phlow/feeling-responsive/blob/gh-pages/images/video-feeling-responsive-1280x720.jpg)](https://www.youtube.com/embed/3b5zCFSmVvU)

## A Responsive Jekyll Theme: *Feeling Responsive*

Do you want to get to know *Feeling Responsive*? Than check it out first and have a look on its home at  <http://phlow.github.io/feeling-responsive/>.

To get to know *Feeling Responsive* check out all the features explained in the [documentation][1].

And what license is *Feeling Responsive* released under? [This one][2].



## Why use this theme?

Feeling Responsive is heavily customizable.

1. Language-Support :)
2. Optimized for speed and it's responsive.
3. Built on Foundation Framework.
4. Six different Headers.
5. Customizable navigation, footer,...

**[More ›][3]**



## Changelog

*Feeling Responsive* is in active development. Thank you to everyone who contributed, especially [Róbert Papp][5], [Alexandra von Criegern](https://github.com/plutonik-a) and [Juan Jose Amor Iglesias](https://github.com/jjamor).

**[Read Changelog ›][6]**



## Video Tutorial

Click the image to [watch the YouTube-Video-Tutorial][4].

[![Start Video](https://github.com/Phlow/feeling-responsive/blob/gh-pages/images/video-feeling-responsive-tutorial-frontpage.jpg)](https://www.youtube.com/watch?v=rLS-BEvlEyY)








 [1]: http://phlow.github.io/feeling-responsive/documentation/
 [2]: https://github.com/Phlow/feeling-responsive/blob/gh-pages/LICENSE
 [3]: http://phlow.github.io/feeling-responsive/info/
 [4]: https://www.youtube.com/watch?v=rLS-BEvlEyY
 [5]: https://github.com/TWiStErRob
 [6]: https://phlow.github.io/feeling-responsive/changelog/
 [7]: http://phlow.github.io/feeling-responsive/
 [8]: http://phlow.github.io/simplicity/
 [9]: #
 [10]: #

 # RM notes
 - Used [this tutorial](https://oncletom.io/2016/travis-ssh-deploy/) for deployment
 - Server location is also encrypted by Travis
