# Saudi AI Team Website
This website is made by the students on the Saudi Team, to preserve history of Saudi AI Team in one place.

This website includes: olympiads, participations, and members.

## Documentation
Read [Website public data files](https://ai.sainformatics.org/data/) documentation.

You might also refer to [Developer documentation](https://ai.sainformatics.org/data/dev).

## Local Build
### Prerequisites
You need:
- [Python Interpreter](https://python.org)
- [Ruby Interpreter](https://www.ruby-lang.org)
- Install Ruby dependencies using [Bundler](https://bundler.io):
```sh
bundle install
```

<details>
    <summary>How does it work?</summary>
    `bundle` is a package manager, `Gemfile` contains the packages list.
    Jekyll latest version is 4.4.1, but the current version used in Github pages is 
</details>

### Building & Local Serving
```sh
python prebuild.py && python build.py && bundle exec jekyll serve -s ./root
```

## Maintainers
This website needs people who maintain the data up-to-date.

Current maintainers:
- Muaath Alqarni

Data Contributers:
- Layth Alzahrani

## License
This project is licensed under the GNU General Public License v3.0.

Check [LICENSE](https://github.com/informatics-sa/ai-website/blob/main/LICENSE)