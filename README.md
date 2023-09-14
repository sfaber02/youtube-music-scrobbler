# YTMUSIC API

YTMusic Api is a python package to get your Youtube Music history of the last week

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the dependencies.

```bash
pip install -r requirements.txt
```

## Usage

After you have installed the dependencies, run:

```bash
ytmusicapi oauth
```

And follow the instructions. This will create a file `oauth.json` in the current directory.

After that, you must [create an API key for last.fm](https://www.last.fm/api/account/create) and create an `.env` file, filling the required information

Then run:

```bash
python start.py
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
