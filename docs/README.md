# L'edge GPT

Forked from [acheong08/EdgeGPT](https://github.com/acheong08/EdgeGPT), with some personal tweaks.

## Download & Install

```bash
$ wget 'https://raw.githubusercontent.com/KevCui/EdgeGPT/master/src/EdgeGPT.py'
$ chmod +x EdgeGPT.py
$ pip install certifi httpx prompt_toolkit requests rich websockets
```

## Configuration

1. Sign in Bing chat in browser
2. Get `_U` cookie value
3. Put `_U` cookie value in JSON string below and save it as a JSON file:

```json
[
  {
    "name": "_U",
    "value": "<your_cookie_value>"
  }
]
```

## Usage

```bash
$ ./EdgeGPT.py --cookie-file <your_cookie_file> --help
```
