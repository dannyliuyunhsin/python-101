# Python 101 Tutorial

![GitHub Pipenv locked Python version](https://img.shields.io/github/pipenv/locked/python-version/violetvivirand/python-101)

Python lectures for begineers

# Contributing

Lock dependencies before submit changes:

```bash
# Freeze into requirements.txt with Poetry
poetry export -f requirements.txt --output requirements.txt

# Use dephell to convert between different formats
# Convert from Poetry (pyproject.toml) to Pipfile
dephell deps convert --from-format=poetry --from-path=pyproject.toml  --to-format=pipfile --to-path=Pipfile
# Convert from Poetry Lock (poetry.lock) to Pipfile.lock
dephell deps convert --from-format=poetrylock --from-path=poetry.lock  --to-format=pipfilelock --to-path=Pipfile.lock
```

## License

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:cc="http://creativecommons.org/ns#" class="license-text"><a rel="cc:attributionURL" property="dct:title" href="https://github.com/VioletVivirand/python-101">Python 101</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/VioletVivirand">Violet Vivirand</a> is licensed under <a rel="license" href="https://creativecommons.org/licenses/by-nc/4.0">CC BY-NC 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" /></a></p>
