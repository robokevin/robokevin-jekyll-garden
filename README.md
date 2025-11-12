# Jekyll Garden

A simple Jekyll theme that turns your Obsidian notes into a beautiful website. Perfect for sharing your thoughts and knowledge online. If you use Obsidian for note-taking, this theme makes it easy to publish your markdown files as a connected website with wiki-style links and full-text search.

Setup steps:

1. Fork jekyll-garden.
2. Clone Github repo to computer.
3. Copy paste code from [Bill Raymond's Docker tutorial](https://gist.github.com/BillRaymond/db761d6b53dc4a237b095819d33c7332#file-dockerfile) into Dockerfile.
4. Make a file called .ruby-version with "3.1.2" inside. (That's what Bill Raymond is using), and makes Netlify use that Ruby version.
5. Run bundle install.
6. Deploy on Netlify.
7. Setup custom domain on domain registrar.


Modifications to theme:

- Added github link to footer
- Added a appearances variable for spacing between info
- Added a contact page

Next steps:

1. Figure out how to not have to Bundle install everytime.
2. How to make it run live reload automatically when I start the Docker container.
3. Make dark-mode the default theme.


   
