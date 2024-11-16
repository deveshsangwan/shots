[![Update from Instagram](https://github.com/deveshsangwan/shots/actions/workflows/updateFromInstagram.yml/badge.svg)](https://github.com/deveshsangwan/shots/actions/workflows/updateFromInstagram.yml)

[![Photography](https://img.shields.io/badge/Photography-Shots-black?style=for-the-badge)](https://deveshsangwan.github.io/shots/)
# Shots
A tracker and ad free version of [rampatra/photography](https://github.com/rampatra/photography) with automations. You can set up [Zapier Workflow](https://zapier.com/shared/5617774e53ce7454c52e31623571912a4cae6d5e) which will connect to Instagram.

## Highlights
1. Easy setup and you get a site of your own for __free__.
2. To add new pictures, you need to just upload them. __No code__ changes required.
3. This I like the most, you get to see EXIF data like __aperture, shutter speed, iso__ etc when you click on any image automagically.

## Quick Start
If you know a tad about tech and love taking pictures then this open-source project may help you setup a website to showcase
all your creations without effort. And not just that, with this you need not pay a single dime to host your website as
it's hosted by GitHub for __free__.

**Just follow the below steps and your website would be live in no time:**

1. Fork this repo by hitting the `Fork` button at the top right corner.
2. Enable github pages from the repo settings.
3. Upload your pictures to `images` directory. And a Github Action will add the photos where it needs to be.
4. Add your own custom domain in `CNAME` file or just remove the file if you don't own a domain and use the default domain that github provides ([yourusername].github.io/photography).
5. Update `baseurl` field in `_config.yml` file with whatever domain you used in step 4.
6. And that's it, your website is set. To view, go to [deveshsangwan.github.io/shots/](https://deveshsangwan.github.io/shots/) (or whatever you have in the CNAME file) and if you don't have one, you can go to [[yourusername].github.io/photography](http://yourusername.github.io/photography)

You can change my name in `_config.yml` file.
 
## ProTips

1. Fork and then clone the project to your computer
2. Go inside the project `$ cd shots`
3. Install all dependencies by `$ npm install`
4. Copy all your pictures (possibly jpg, the largest size available, straight from your camera) and put it inside `images` directory
5. Run `$ gulp` to resize the images and to generate thumbnails automatically
6. Push your changes to github.com by `$ git add --all` and `$ git commit -m "a nice commit message"` and then finally `$ git push origin master`

## Acknowledgment
All the credit for this website goes to [Ram](https://github.com/rampatra).
