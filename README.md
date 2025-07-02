# bakerHerrin.github.io

To compile the website: 

- bundle exec jekyll serve --livereload

Run on the base system. No need for a venv or mamba/conda env.
To view locally, once compiled a URL will be generated.


Once pushed, the website will be deployed via github-pages.


TROUBLESHOOTING:

I had to export GEM_HOME before Jekyll is recognized.
- export GEM_HOME="$HOME/.gem"