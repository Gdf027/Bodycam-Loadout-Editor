# Bodycam Loadout Editor

**[English](#english) · [Русский](#русский)**

---

## English

A loadout editor for **Bodycam**: change weapons, skins, attachments, operators and knives right in the `Loadout.sav` save file. For game version **0.9.1**.

### Download

Download `BodycamLoadoutEditor_v6.2.zip` from **[Releases](../../releases/latest)**, unpack it and run `BodycamLoadoutEditorV6.exe`. No installation needed.

**VirusTotal check of the zip:** [0 / 61 detections](https://www.virustotal.com/gui/file/6cfd312b88184325b7283cd2d5f51425e7b68daa6ae1e39061f86c0f58c487f0) (v6.2, SHA256 `6cfd312b…c487f0`)

### Features

- **3258 items** with icons: 141 weapons, 237 skins, 2770 attachments, 110 operators. English and Russian interface.
- **Slots as in the game.** Each weapon has its own slots; empty slots can be filled.
- **Full skin in one click**: the receiver and every part of a shop skin set.
- **"To all loadouts"**: copy an operator or a knife from one loadout to all the others.
- **Stats** for weapons and attachments.
- **Loadouts**: same order as in the game, copy and delete (up to 7).
- **Safe saving**: a `Loadout.sav.bak` copy is made before writing, and the file is checked byte for byte.

### How to use

1. **Close the game.** If it is running, the editor warns you before saving: the game may overwrite the save with its own.
2. Start the editor — it opens the save from `%LOCALAPPDATA%\Bodycam\Saved\SaveGames\Loadout.sav`.
3. Expand a loadout, click a field and pick an item.
4. Press **SAVE** and start the game.

The ⟲ button resets a field to its original value; "RELOAD" discards all unsaved changes.

### Notes

- The editor only changes the save file on your PC and never touches the game process.
- If something goes wrong: delete `Loadout.sav` and rename `Loadout.sav.bak` to `Loadout.sav` by removing `.bak` from the name. Both files are in `%LOCALAPPDATA%\Bodycam\Saved\SaveGames`.
- A game update may change the save format — wait for a new editor version.
- Some antivirus engines may flag the exe: this happens with unsigned programs built with PyInstaller. See the VirusTotal report above.
- Use at your own risk. This is an unofficial project, not affiliated with the Bodycam developers.

Video about the editor: https://youtu.be/GGpe8O6waDg

---

## Русский

Редактор лодаутов для игры **Bodycam**: оружие, скины, модули, операторы и ножи прямо в файле сохранения `Loadout.sav`. Для версии игры **0.9.1**.

### Скачать

Скачайте `BodycamLoadoutEditor_v6.2.zip` во вкладке **[Releases](../../releases/latest)**, распакуйте и запустите `BodycamLoadoutEditorV6.exe`. Установка не нужна.

**Проверка zip на VirusTotal:** [0 из 61 срабатываний](https://www.virustotal.com/gui/file/6cfd312b88184325b7283cd2d5f51425e7b68daa6ae1e39061f86c0f58c487f0) (v6.2, SHA256 `6cfd312b…c487f0`)

### Что умеет

- **3258 предметов** с иконками: 141 оружие, 237 скинов, 2770 модулей, 110 операторов. Интерфейс на русском и английском.
- **Слоты как в игре.** У каждого оружия свои слоты; пустые слоты можно заполнить.
- **Полный скин одним нажатием**: ресивер и все детали набора из магазина.
- **«На все лодауты»**: оператор или нож из одного лодаута ставится во все остальные.
- **Характеристики** оружия и деталей.
- **Лодауты**: порядок как в игре, копия и удаление (до 7 штук).
- **Безопасное сохранение**: перед записью рядом создаётся копия `Loadout.sav.bak`, файл проверяется байт в байт.

### Как пользоваться

1. **Закройте игру.** Если она запущена, редактор предупредит перед сохранением: игра может перезаписать сейв своим.
2. Запустите редактор — сейв откроется сам из `%LOCALAPPDATA%\Bodycam\Saved\SaveGames\Loadout.sav`.
3. Раскройте лодаут, нажмите на поле и выберите предмет.
4. Нажмите **СОХРАНИТЬ** и запустите игру.

Кнопка ⟲ возвращает поле к исходному значению, «ПЕРЕЧИТАТЬ» отменяет все несохранённые правки.

### Важно

- Редактор меняет только файл сохранения на вашем компьютере и не трогает процесс игры.
- Если что-то пошло не так: удалите `Loadout.sav` и переименуйте `Loadout.sav.bak` в `Loadout.sav`, убрав `.bak` из имени. Оба файла лежат в `%LOCALAPPDATA%\Bodycam\Saved\SaveGames`.
- После обновления игры формат сейва может измениться — дождитесь новой версии редактора.
- Некоторые антивирусы могут ругаться на exe: так бывает с неподписанными программами, собранными PyInstaller. Смотрите отчёт VirusTotal выше.
- Пользуетесь на свой страх и риск. Проект неофициальный и не связан с разработчиками Bodycam.

Видео про редактор: https://youtu.be/GGpe8O6waDg
