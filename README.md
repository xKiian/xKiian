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
<img src="https://raw.githubusercontent.com/xkiian/profile-summary-cards/master/profile-summary-card-output/nord_dark/3-stats.svg" width="32.5%" style="display: inline-block; margin: 0 10px;">
<img src="https://raw.githubusercontent.com/xkiian/profile-summary-cards/master/profile-summary-card-output/nord_dark/1-repos-per-language.svg" width="32.5%" style="display: inline-block; margin: 0 10px;">
<img src="https://raw.githubusercontent.com/xkiian/profile-summary-cards/master/profile-summary-card-output/nord_dark/2-most-commit-language.svg" width="32.5%" style="display: inline-block; margin: 0 10px;">
</div>
