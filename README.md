# Source code for algalsexlab.info

This is the source code for my personal site
[algalsexlab.info](http://algalsexlab.info).

## Dependencies

You'll need to install [Nēnē](https://nene.leouieda.com/) and all it's
dependencies to build the site. I have been using Python 3.9 for the build. See
`environment.yml` for the complete dependency list.

You can create a conda environment with all required dependencies by running
`conda env create` in the root of the repository. To activate the environment
so we can run the build use `source activate leouieda.com`.

## Compiling the site

To build the website:

```
nene
```

To serve the website to localhost for development:

```
nene -s
```

## The theme

The website theme custom made with pure CSS.
Icons are provided by [FontAwesome](http://fontawesome.io/) and
[Academicons](http://jpswalsh.github.io/academicons/).
The font used is [Atkinson Hyperlegible](https://brailleinstitute.org/freefont).

The Jinja2 templates and CSS are located in the `_templates` and `css` folders.
I really should make this theme more generic and provide it to the world.
But, you know, time and things.
You can still use it by copying the folders to your own project.
I can't guarantee that things will work without my specific folder structure.

## Automatic deploy with GitHub Actions

The site is automatically built and deployed to
[Chlamy18/Chlamy18.github.com](https://github.com/Chlamy18/Chlamy18.github.com)
every time a commit is pushed to the *main* branch.
See files `.github/workflows/build.yml`.

## License

Except were otherwise noted, this work is licensed under a
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
