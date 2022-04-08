# 🎩 No Cap
> A python module to solve all sorts of pesky captchas. We <3 bots.


## 📜 General Information
No Cap is a Python package for solving captchas. This libary is perfect for crawlers, automated bots, etc. Our goal? Give automated bot developers more freedom and control.


## 💾 Technologies Used
- Python 3.9
- Pyppeteer
- YOLO v5


## 🚀 Features
What makes No Cap so great?
- Solves 1-2 step hCaptcha directly or with a browser. 
- Multi-proccessing utilized for maximum object recognition speed. 
- Safe delay speeds to prevent flags.
- Only 1-3 lines to solve a captcha.


## 🌸 Demo
**COMING SOON**


## 🧰 Setup
No Cap is a Python package, so it can be easily installed with [Pypi](https://pypi.org) or directly from the repo.

```txt
pip install nocap
```

```txt
pip install git+https://github.com/GalaxzyDev/No-Cap
```


## 🏁 Usage

> **Solving hCaptcha Directly**
```py
from nocap import HcaptchaDirect

hcaptcha = HcaptchaDirect(
  domain  =  ""  # Domain name (eg. discord.com)
  sitekey =  ""  # hCaptcha site key
)

token = hcaptcha.solve()
# print(token)
```


## 🟢 Project Status
Currently only hCaptcha is supported, multiple captcha support planned.


## 🤝 Acknowledgements
- This project was inspired by [Go Hcaptcha](https://github.com/JustTalDevelops/go-hcaptcha)
