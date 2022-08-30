![Mt Hood SAR Council with mountain and plus sign](https://mhsarc.github.io/mhsarc/assets/images/mhsarc.jpg)

# Mt. Hood Search and Rescue Council

This is the repository for the Mt. Hood Search and Rescue Council. The council exists to save lives and improve search and rescue practices with our nine Oregon County Sheriff offices, volunteer rescue teams, and other collaborators.

## The website
This site uses a static site generator ([Jekyll](https://jekyllrb.com/)) and the [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/).

### License
[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/mmistakes/minimal-mistakes/master/LICENSE)

### How to update
We're working on configuring a content management system for the site, but in the meantime, if you have a GitHub account and you've been added to the MHSARC organization with write access, you can edit files using the GitHub web interface. If you have a GitHub account and don't have write access, you can still edit content, and open a pull request to submit changes for review.

#### Content
Site content is mostly contained in three folders:

- `_pages` - all pages (except the homepage) in [markdown format](https://www.markdowntutorial.com/)
- `_data` - sponsors (in YAML format - pay attention to indents and maintain the spacing you see)
- `_posts` - news content (blog posts)

##### Images
- `assets` - contains the `images` directory, where images are stored

##### Homepage content
- `index.html` - homepage

Most of the content on the homepage is in the front matter of `index.html`. Front matter is separated by three hyphens and the top of the file and three at the end.