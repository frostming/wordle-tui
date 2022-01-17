# Wordle TUI

Play [WORDLE] game in your terminal.

**The game will be kept the same as the Web version.**

## Quick Start

Clone the repository

```bash
git clone https://github.com/frostming/wordle-tui.git
cd wordle-tui
```

If you are using [PDM](https://pdm.fming.dev), then:

```bash
pdm install
# Run the application
pdm run start
```

Otherwise, set up a new virtualenv and install the only dependency `textual`:

```bash
python3 -m venv venv
. venv/bin/activate
pip install textual
# Run the application
python wordle_app.py
```

Or, if you want to install this application:

```bash
pip install "git+https://github.com/frostming/wordle-tui.git#egg=wordle-tui"
```

## Credits

- [Wordle]
- [Rich]
- [Textual]

[wordle]: https://www.powerlanguage.co.uk/wordle/
[rich]: https://github.com/Textualize/rich)
[textual]: https://github.com/Textualize/textual

Special Thanks to [@willmcgugan](https://github.com/willmcgugan) who created the awesome tools.

## Todo List

- [ ] Share the result

## License

MIT.
