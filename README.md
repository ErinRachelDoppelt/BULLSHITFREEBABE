# IOC Jekyll Starter theme

For detailed instructions and videos, please see the IOC Student Hub. This readme will just contain a few important notes.

The starter theme uses:
- jekyll
- Gridlex for the flexbox grid
- snipcart for eCommerce
- lightwidget for the instagram widget
- lightbox2 for the pop-up images in the shop
- the jekyll-archives plugin to generate category archive pages automatically
- the jekyll-paginate plugin to automatically paginate old blog posts in the archive folder

Because the starter theme uses plugins, the process for running jekyll in terminal is slightly different.

1. In terminal navigate to your folder as normal
2. Run `bundle install`. This will download and install all the plugins
3. To ensure that you run jekyll using the right plugins each time, instead of just entering `jekyll serve` you will now enter `bundle exec jekyll serve` each time
4. Remember that if you make any changes to the _config.yml file then you need to restart terminal by entering `control C` and then re-entering `bundle exec jekyll serve`

As this is a new theme that hasn't been tested extensively, please let us know if you find any bugs, or any of the code confusing.

You may notice a few different files including a GEMFILE and GEMFILE.lock, these are both related to the two jekyll plugins used. 
