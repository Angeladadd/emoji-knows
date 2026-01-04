# emoji-knows-everything

Hide and reveal secret messages using emojis!

## Usage

### Encode - Hide a message in an emoji

```
encode.html?text=<message>&emoji=<emoji>
```

- **text** (required): The secret message you want to hide
- **emoji** (optional): The emoji container. Default is 💩

**Example:**
```
http://localhost:8000/encode.html?text=secret&emoji=🎉
```

### Decode - Reveal a hidden message

```
decode.html?emoji=<emoji>
```

- **emoji** (required): The emoji containing your hidden message

**Example:**
```
http://localhost:8000/decode.html?emoji=🎉​‌‌‌​​‌‌​‌‌​​‌​‌​‌‌​​​‌‌​‌‌‌​​‌​​‌‌​​‌​‌​‌‌‌​‌​​
```

## Test Locally

To test the website locally, run a simple HTTP server from the project directory:

```bash
cd <path to>/emoji-knows-everything
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.
