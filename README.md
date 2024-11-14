<h1>Somnium <a href="#Favicon"><img src="" width="33px"></a></h1>
<p>Unlimited Image generation using cloudflare workers.</p>

<br>

## 🗜 Features
<!-- - **Clear Chat**: Start a new conversation at any time.
- **Settings**: Toggle particle effects and theme settings (light/dark).
- **Open Source Contributions**: Open to community contributions for further improvements. -->

<br>

## ⚙️ Deploy
- Create a [Cloudflare](https://www.cloudflare.com/) **account**.
- Navigate to `Workers & Pages > Create > Create Worker`.
- Deploy the worker by clicking **Deploy**.
- Edit the code by clicking **Edit Code**.
- Upload [worker.js](https://github.com/ZAR0X/Somnium/blob/main/worker/worker.js) into **Cloudflare**.
- Finally, **Deploy**.

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/ZAR0X/Somnium)

<br>

## 📡 Live Demo
Check out the live demo [here](https://zarox.is-a.dev/somnium).

<br>

## 📷 Screenshot
<a href="#Screenshot"><img src="" width="1612px"></a>

<br>

## 📦 Python Usage ([pip package](https://pypi.org/project/somnium/))
- **Author**: [Vauth](https://github.com/vauth)

### Installation:
```bash
python3 -m pip install somnium
```

```python
if __name__ == "__main__":
   from somnium import Somnium

    # Get Styles (url)
    print(Somnium.StylesGraph())

    # Get Styles (list)
    print(Somnium.Styles())

    # Generate Artwork
    print(Somnium.Generate('Hunter Schafer', 2009))
```

<br>

## 🛠 Credits
- **Front-End Developer & Somnium API**: [Zarox](https://github.com/Zar0x) ([Somnium-gui](https://github.com/Zar0x/somnium-gui))
- **Back-End Developer**:  [Vauth](https://github.com/vauth)

<br>

## 🔗 Contributing
Contributions are welcome! Feel free to submit a pull request or report an issue.

<br>

## 🔎 License
```
MIT License

Copyright (c) 2024 Vauth

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
