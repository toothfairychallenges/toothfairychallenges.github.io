# toothfairychallenges.github.io

## Description

This is the official repository for the ToothFairy Challenges homepage.
Visit our website at [toothfairychallenges.github.io](https://toothfairychallenges.github.io/).

## Local build and test
```bash
bundle install
bundle exec jekyll serve
```

`bundle install` has error for `An error occurred while installing mini_racer (0.6.3)`

possible workaround:
- Installing Node.Js (`node -v # v19.7.0`)
- Commented out `gem 'mini_racer'`

see github issue [libv8-node error](https://github.com/alshedivat/al-folio/issues/691)

## Update Content

Pages relevant for the content update (basically all in `_pages` dir):
- `CoWBenchmark.github.io/_pages/about.md`
- `_config.yml`
- `_news/`
- later if needs to include publications, `_bibliography/papers.bib`

## GitHub Pages Deploy

If you encounter `Liquid Exception: Liquid syntax error`, that is likely due to the deploy branch not set to `gh-pages` on github
> "Finally, in the Settings of your repository, in the Pages section, set the branch to gh-pages (NOT to master). For more details, see Configuring a publishing source for your GitHub Pages site."

## References

- Jekyll template used: [al-folio](https://github.com/alshedivat/al-folio)
- Video tutorial: [using Jekyll with the al-folio template](https://www.youtube.com/watch?v=g6AJ9qPPoyc)
