<img src="https://komarev.com/ghpvc/?username=sfx2me&label=Profile%20Views&color=008042&style=flat&label=Visitors" alt="Visitors">

```python
from abc import ABCMeta, abstractstaticmethod


class IxKian(metaclass=ABCMeta):
    @abstractstaticmethod
    def contact():
        return ["discord", "telegram"]

    @abstractstaticmethod
    def life():
        return self.coding()

    @abstractstaticmethod
    def coding():
        pass


class Attributes(IxKian):
    @staticmethod
    def contact() -> tuple:
        discord: str = ".xkian"
        telegram: str = "xKian"

        return discord, telegram

    @staticmethod
    def life() -> tuple:
        langs = ("German", "English")

        return langs

    @staticmethod
    def coding() -> tuple:
        text_editor = "vscode"
        specialities = ["reverse engineering", "automation"]
        langs = {"pro": "python", "intermediate": "go", "learning": "js"}
        return langs, specialities, text_editor
```
<div style="text-align: center;">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=xkiian&theme=tokyonight" width="30%" style="display: inline-block; margin: 0 5px;">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=xkiian&theme=tokyonight" width="30%" style="display: inline-block; margin: 0 5px;">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=xkiian&theme=tokyonight&utcOffset=1" width="30%" style="display: inline-block; margin: 0 5px;">
</div>


