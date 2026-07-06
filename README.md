# Retro Gamepad Skins for GamepadViewer

<img width="100%" src="https://raw.githubusercontent.com/frolovlife/frolovlife/refs/heads/main/assets/projects/gamepadviewer-skins/social-preview_gamepadviewer-skins.png">

These are custom skins of various controllers (retro and some new) for [GamepadViewer](https://gamepadviewer.com/). You can use them to display the buttons that are being pressed on your stream as an overlay.

> [!IMPORTANT]
> GamepadViewer works with XInput controllers. Work with DirectInput controllers is not guaranteed.
>
> Unfortunately, GamepadViewer doesn't support `LP`, `RP`, `L4`, and `R4`. Therefore, it's impossible to create a skin that supports these buttons.

From time to time, I'll be tweaking existing skins and adding new ones. You can star the repository so you don't lose this skins.

## 📺 How to use with OBS Studio, StreamLabs etc.

1. Choose the controller skin you want to display on your stream below.
2. Copy the link for OBS Studio with or without mapping, as needed.<br>*Some controllers, such as the 8BitDo M30, don't have analog sticks, but their D-pad functions as the left stick. To ensure proper operation with these controllers, use the link with mapped L-stick to D-pad.*
3. Add a Browser source on the scene in OBS Studio:
    - Right click in `Sources` → `Add` → `Browser`.
    - Name it as you want (i.e.: «Gamepad»).
    - Paste the previously copied link into the URL field and click `OK`.
4. Adjust size, scale and position of the Browser source as you wish.
> [!TIP]
> All links for OBS Studio assume the use of the first player's controller. To display the second, third, or fourth player's controller, replace `p=1` in the link with `p=2`, `p=3`, or `p=4` respectively.

## 🔧 How to use with GamepadViewer's URL generator

1. Choose the controller skin you want to display on your stream below.
2. Copy the raw CSS link of these skin.
3. Go to [GamepadViewer URL Generator](https://gamepadviewer.com/#generate).
4. Paste the copied link into the «Custom CSS URL» field.
5. Configure the remaining parameters as desired and copy the generated link.
6. Paste the generated link into the Browser source address bar in OBS Studio and click `OK`.

# 🎮 Controller skins

- [**8BitDo**](#8bitdo)
  - 8BitDo Pro 2: [grey](#8bitdo-pro-2-grey-%EF%B8%8F), [classic](#8bitdo-pro-2-classic-%EF%B8%8F), [black](#8bitdo-pro-2-black-%EF%B8%8F)
  - 8BitDo Pro 3: [grey](#8bitdo-pro-3-grey-%EF%B8%8F), [classic](#8bitdo-pro-3-classic-%EF%B8%8F), [purple](#8bitdo-pro-3-purple-%EF%B8%8F), [orange](#8bitdo-pro-3-orange-%EF%B8%8F)
  - 8BitDo M30: [black](#8bitdo-m30-black-%EF%B8%8F), [white](#8bitdo-m30-white-%EF%B8%8F)
- [**Sega**](#sega)
  - Sega Mega Drive 2 / Genesis 2: [Japan/Asia](#sega-mega-drive-2-japanasia-%EF%B8%8F), [USA](#sega-genesis-2-%EF%B8%8F), [Europe](#sega-mega-drive-2-europe-%EF%B8%8F)
  - Sega Saturn model 2: [black](#sega-saturn-model-2-black-%EF%B8%8F), [white](#sega-saturn-model-2-white-%EF%B8%8F), [gray](#sega-saturn-model-2-gray-%EF%B8%8F)
  - Sega Saturn 3D: [black](#sega-saturn-3d-black), [white](#sega-saturn-3d-white)
  - Sega Dreamcast: [white](#sega-dreamcast-white-%EF%B8%8F), [black](#sega-dreamcast-black-%EF%B8%8F), [super black](#sega-dreamcast-super-black-%EF%B8%8F)
- [**Nintendo**](#nintendo)
  - 8-bit: [Famicom](#famicom), [NES](#nes-%EF%B8%8F), [«Dogbone»](#nes-dogbone)
  - 16-bit: [Super Famicom](#super-famicom), [SNES (USA)](#snes-usa), [SNES (Europe)](#snes-europe)
- [**Sony**](#sony)
  - PlayStation: [grey](#playstation-grey), [black](#playstation-black)
  - DualShock: [grey](#dualshock-grey-%EF%B8%8F), [white](#dualshock-white-%EF%B8%8F)
  - DualShock: [grey](#dualshock-black-%EF%B8%8F), [white](#dualshock-silver-%EF%B8%8F), [white](#dualshock-pink-%EF%B8%8F)
- [**Famiclones**](#famiclones)
  - Dendy: [Classic](#dendy-classic), [Junior (var. 1)](#dendy-junior-var-1), [Junior (var. 2)](#dendy-junior-var-2), [Junior (var. 3)](#dendy-junior-var-3-%EF%B8%8F)
- [**3DO**](#3do)
  - [Panasonic FZ-1](#panasonic-fz-1-%EF%B8%8F), [Sanyo](#sanyo-%EF%B8%8F), [Panasonic FZ-10](#panasonic-fz-10-%EF%B8%8F)
- [**NEC**](#nec)
  - PC Engine / TurboGrafx 16: [PI-PD001](#nec-pc-engine-pi-pd001), [PI-PD002](#nec-pc-engine-pi-pd002), [PI-PD6](#nec-pc-engine-pi-pd6), [PI-PD8](#nec-pc-engine-pi-pd8), [TG 16](#nec-turbografx-16),  [PCE-Duo](#nec-pc-engine-duo), [TurboDuo](#nec-turboduo), [PCE-TP2](#nec-pc-engine-pce-tp2), [PCE-TP1 (Arcade Pad 6)](#nec-pc-engine-pce-tp1-arcade-pad-6)
  - [NEC PC-FX](#nec-pc-fx)
- [**SNK**](snk)
  - Neo-Geo: [MVS](#neo-geo-mvs), [AES](#neo-geo-aes-%EF%B8%8F), [Neo-Geo CD](#neo-geo-cd-%EF%B8%8F)


## 8BitDo

### 8BitDo Pro 2 (grey) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/8bitdo/pro2/gray-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=15&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro2-gray.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro2-gray.css)

### 8BitDo Pro 2 (classic) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/8bitdo/pro2/classic-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=15&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro2-classic.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro2-classic.css)

### 8BitDo Pro 2 (black) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/8bitdo/pro2/black-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=15&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro2-black.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro2-black.css)

### 8BitDo Pro 3 (grey) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/8bitdo/pro3/gray-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=15&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro3-gray.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro3-gray.css)

### 8BitDo Pro 3 (classic) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/8bitdo/pro3/classic-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=15&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro3-classic.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro3-classic.css)

### 8BitDo Pro 3 (purple) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/8bitdo/pro3/purple-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=15&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro3-purple.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro3-purple.css)

### 8BitDo Pro 3 (orange) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/8bitdo/pro3/orange-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=15&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro3-orange.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/pro3-orange.css)

### 8BitDo M30 (black) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/8bitdo/m30/preview-black.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-black.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-black.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-black.css)

### 8BitDo M30 (white) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/8bitdo/m30/preview-white.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-white.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-white.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-white.css)

## Sega

### Sega Mega Drive 2 (Japan/Asia) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/megadrive2/preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/megadrive2.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/megadrive2.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, LT to Mode)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/megadrive2.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"8","disabled":false,"choiceType":"buttons","choice":"6"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/megadrive2.css)

### Sega Genesis 2 ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/megadrive2/preview-usa.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/genesis2.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/genesis2.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, LT to Mode)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/genesis2.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"8","disabled":false,"choiceType":"buttons","choice":"6"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/genesis2.css)

### Sega Mega Drive 2 (Europe) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/megadrive2/preview-eu.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/megadrive2-eu.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/megadrive2-eu.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, LT to Mode)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/megadrive2-eu.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"8","disabled":false,"choiceType":"buttons","choice":"6"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/megadrive2-eu.css)

### Sega Saturn model 2 (black) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/saturn-m2/preview-black.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-black.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-black.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-black.css)

### Sega Saturn model 2 (white) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/saturn-m2/preview-white.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-white.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-white.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-white.css)

### Sega Saturn model 2 (gray) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/saturn-m2/preview-gray.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-gray.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-gray.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-gray.css)

### Sega Saturn 3D (black)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/saturn-3d/preview-black.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-3d-black.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-3d-black.css)

### Sega Saturn 3D (white)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/saturn-3d/preview-white.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-3d-white.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-3d-white.css)

### Sega Dreamcast (white) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/dreamcast/white-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=10&css=https://frolovlife.github.io/gamepadviewer-skins/sega/dreamcast-white.css)
- [For OBS Studio etc. (with mapping: LB to LT, RB to RT)](https://gamepadviewer.com/?p=1&soffset=10&css=https://frolovlife.github.io/gamepadviewer-skins/sega/dreamcast-white.css&map={"mapping":[{"targetType":"buttons","target":"6","disabled":false,"choiceType":"buttons","choice":"4"},{"targetType":"buttons","target":"7","disabled":false,"choiceType":"buttons","choice":"5"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/dreamcast-white.css)

### Sega Dreamcast (black) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/dreamcast/black-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=10&css=https://frolovlife.github.io/gamepadviewer-skins/sega/dreamcast-black.css)
- [For OBS Studio etc. (with mapping: LB to LT, RB to RT)](https://gamepadviewer.com/?p=1&soffset=10&css=https://frolovlife.github.io/gamepadviewer-skins/sega/dreamcast-black.css&map={"mapping":[{"targetType":"buttons","target":"6","disabled":false,"choiceType":"buttons","choice":"4"},{"targetType":"buttons","target":"7","disabled":false,"choiceType":"buttons","choice":"5"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/dreamcast-black.css)

### Sega Dreamcast (super black) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/dreamcast/superblack-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=10&css=https://frolovlife.github.io/gamepadviewer-skins/sega/dreamcast-sblack.css)
- [For OBS Studio etc. (with mapping: LB to LT, RB to RT)](https://gamepadviewer.com/?p=1&soffset=10&css=https://frolovlife.github.io/gamepadviewer-skins/sega/dreamcast-sblack.css&map={"mapping":[{"targetType":"buttons","target":"6","disabled":false,"choiceType":"buttons","choice":"4"},{"targetType":"buttons","target":"7","disabled":false,"choiceType":"buttons","choice":"5"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/dreamcast-sblack.css)


## Nintendo

### Famicom

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/famicom/preview-famicom.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/famicom/preview-famicom-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom-xy.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom-xy.css)

### NES ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/nes/preview.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/nes/preview-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes-xy.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes-xy.css)

### NES «Dogbone»

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/dogbone/preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/dogbone.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/dogbone.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/dogbone.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/dogbone.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/dogbone.css)

### Super Famicom

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/snes/preview-sfc.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/sfc.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/sfc.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, LT to RB)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/sfc.css&map={"mapping":[{"targetType":"buttons","target":"5","disabled":false,"choiceType":"buttons","choice":"6"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/sfc.css)

### SNES (USA)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/snes/preview-snes.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, LT to RB)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes.css&map={"mapping":[{"targetType":"buttons","target":"5","disabled":false,"choiceType":"buttons","choice":"6"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes.css)

### SNES (Europe)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/snes/preview-snes-eu.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes-eu.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes-eu.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, LT to RB)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes-eu.css&map={"mapping":[{"targetType":"buttons","target":"5","disabled":false,"choiceType":"buttons","choice":"6"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes-eu.css)

## Sony

### PlayStation (grey)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sony/playstation/grey-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sony/playstation-grey.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sony/playstation-grey.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sony/playstation-grey.css)

### PlayStation (black)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sony/playstation/black-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sony/playstation-black.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sony/playstation-black.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sony/playstation-black.css)

### DualShock (grey) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sony/dualshock/grey-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sony/dualshock-grey.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sony/dualshock-grey.css)

### DualShock (white) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sony/dualshock/white-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sony/dualshock-white.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sony/dualshock-white.css)

### DualShock 2 (black) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sony/dualshock2/black-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sony/dualshock2-black.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sony/dualshock2-black.css)

### DualShock 2 (silver) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sony/dualshock2/silver-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sony/dualshock2-silver.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sony/dualshock2-silver.css)

### DualShock 2 (pink) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sony/dualshock2/pink-preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sony/dualshock2-pink.css)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sony/dualshock2-pink.css)


## Famiclones

### Dendy Classic

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/famiclones/dendy-classic/preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-classic.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-classic.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-classic.css)

### Dendy Junior (var. 1)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/famiclones/dendy-junior/preview-v1.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v1.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v1.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v1.css)

### Dendy Junior (var. 2)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/famiclones/dendy-junior/preview-v2.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v2.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v2.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v2.css)

### Dendy Junior (var. 3) ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/famiclones/dendy-junior-v3/preview-v3.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v3.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v3.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v3.css)


## 3DO

### Panasonic FZ-1 ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/3do/panasonic/preview-fz1.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=15&css=https://frolovlife.github.io/gamepadviewer-skins/3do/fz1.css)
- [For OBS Studio etc. (with mapping: Y to A)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/3do/fz1.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"3"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, LT to RB, Y to A, RB to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/3do/fz1.css&map={"mapping":[{"targetType":"buttons","target":"5","disabled":false,"choiceType":"buttons","choice":"6"},{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"5"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]}) (for 8BitDo M30)
- [For OBS Studio etc. (with mapping: L-stick to D-pad, LT to RB, A to X, B to A, RT to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/3do/fz1.css&map={"mapping":[{"targetType":"buttons","target":"5","disabled":false,"choiceType":"buttons","choice":"6"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"7"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/3do/fz1.css)

### Sanyo ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/3do/panasonic/preview-sanyo.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=15&css=https://frolovlife.github.io/gamepadviewer-skins/3do/sanyo.css)
- [For OBS Studio etc. (with mapping: Y to A)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/3do/sanyo.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"3"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, LT to RB, Y to A, RB to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/3do/sanyo.css&map={"mapping":[{"targetType":"buttons","target":"5","disabled":false,"choiceType":"buttons","choice":"6"},{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"5"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]}) (for 8BitDo M30)
- [For OBS Studio etc. (with mapping: L-stick to D-pad, LT to RB, A to X, B to A, RT to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/3do/sanyo.css&map={"mapping":[{"targetType":"buttons","target":"5","disabled":false,"choiceType":"buttons","choice":"6"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"7"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/3do/sanyo.css)

### Panasonic FZ-10 ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/3do/panasonic/preview-fz10.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&soffset=15&css=https://frolovlife.github.io/gamepadviewer-skins/3do/fz10.css)
- [For OBS Studio etc. (with mapping: Y to A)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/3do/fz10.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"3"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, LT to RB, Y to A, RB to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/3do/fz10.css&map={"mapping":[{"targetType":"buttons","target":"5","disabled":false,"choiceType":"buttons","choice":"6"},{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"5"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]}) (for 8BitDo M30)
- [For OBS Studio etc. (with mapping: L-stick to D-pad, LT to RB, A to X, B to A, RT to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/3do/fz10.css&map={"mapping":[{"targetType":"buttons","target":"5","disabled":false,"choiceType":"buttons","choice":"6"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"7"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/3do/fz10.css)


## NEC

### NEC PC Engine PI-PD001

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd001.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd001-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd001.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd001.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd001.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd001.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd001.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd001-xy.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd001-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd001-xy.css)

### NEC PC Engine PI-PD002

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd002.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd002-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd002.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd002.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd002.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd002.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd002.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd002-xy.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd002-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd002-xy.css)

### NEC PC Engine PI-PD6

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd6.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd6-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd6.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd6.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd6.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd6.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd6.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd6-xy.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd6-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd6-xy.css)

### NEC PC Engine PI-PD8

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd8.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd8-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd8.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd8.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd8.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd8.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd8.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd8-xy.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd8-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd8-xy.css)

### NEC TurboGrafx 16

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-tg16.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-tg16-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16-xy.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/tg16-xy.css)

### NEC PC Engine Duo

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pce-duo.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pce-duo-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo-xy.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo-xy.css)

### NEC TurboDuo

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-td.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-td-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/td.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td-xy.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/td-xy.css)

### NEC PC Engine PCE-TP2

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-duo-r.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-duo-r-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: L-stick to D-pad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r-xy.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r-xy.css)

### NEC PC Engine PCE-TP1 (Arcade Pad 6)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pce-tp1/preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-tp1.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-tp1.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pce-tp1.css)

### NEC PC-FX

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-fx/preview-pcfx.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pc-fx.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pc-fx.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pc-fx.css)


## SNK

### Neo-Geo MVS

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/snk/mvs/preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/snk/mvs.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/snk/mvs.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/snk/mvs.css)

### Neo-Geo AES ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/snk/aes/preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/snk/aes.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/snk/aes.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/snk/aes.css)

### Neo-Geo CD ✔️

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/snk/neogeo-cd/preview-v1.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/snk/neogeo-cd-v1.css)
- [For OBS Studio etc. (with mapping: L-stick to D-pad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/snk/neogeo-cd-v1.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/snk/neogeo-cd-v1.css)

---

*This project is not affiliated, associated, authorized, endorsed by, or in any way officially connected with 8BitDo, Nintendo, Sony, Sega, SNK, NEC, Panasonic, Sanyo etc. All product, company names and logos are trademarks™ or registered® trademarks of their respective owners.*
