# Collection of screenshots for the presentation

https://carbon.now.sh/

## Configuration

```json
{
  "paddingVertical": "22px",
  "paddingHorizontal": "29px",
  "backgroundImage": null,
  "backgroundImageSelection": null,
  "backgroundMode": "color",
  "backgroundColor": "rgba(171,195,172,1)",
  "dropShadow": true,
  "dropShadowOffsetY": "23px",
  "dropShadowBlurRadius": "68px",
  "theme": "night-owl",
  "windowTheme": "bw",
  "language": "python",
  "fontFamily": "Fira Code",
  "fontSize": "18px",
  "lineHeight": "141%",
  "windowControls": true,
  "widthAdjustment": true,
  "lineNumbers": true,
  "firstLineNumber": 1,
  "exportSize": "4x",
  "watermark": false,
  "squaredImage": false,
  "hiddenCharacters": false,
  "name": "",
  "width": 714.25
}
```

## Snippets

[Population raw 1]()

[Population raw 2](https://carbon.now.sh/?bg=rgba%28171%2C195%2C172%2C1%29&t=night-owl&wt=bw&l=python&width=714.25&ds=true&dsyoff=23px&dsblur=68px&wc=true&wa=true&pv=22px&ph=29px&ln=true&fl=1&fm=Fira+Code&fs=18px&lh=141%25&si=false&es=4x&wm=false&code=import%2520pyam%250A%250Aconnection_name%2520%253D%2520%2522ssp%2522%250Aconn%2520%253D%2520pyam.iiasa.Connection%28connection_name%29%250A%250Amodel%2520%253D%2520%2522IIASA-WiC%2520POP%25202023%2522%250Avariable%2520%253D%2520%2522Population%2522%250Aregion%2520%253D%2520%2522World%2522%250Ascenario%2520%253D%2520%255B%2522SSP1%2522%252C%2520%2522SSP2%2522%252C%2520%2522SSP3%2522%252C%2520%2522SSP4%2522%252C%2520%2522SSP5%2522%255D%250A%250Araw_population%2520%253D%2520conn.query%28%250A%2520%2520%2520%2520variable%253Dvariable%252C%250A%2520%2520%2520%2520model%253Dmodel%252C%250A%2520%2520%2520%2520scenario%253Dscenario%252C%250A%2520%2520%2520%2520region%253Dregion%252C%250A%29)

[PIL](https://carbon.now.sh/?bg=rgba%28171%2C195%2C172%2C1%29&t=night-owl&wt=none&l=python&width=714.25&ds=true&dsyoff=20px&dsblur=68px&wc=true&wa=true&pv=56px&ph=56px&ln=true&fl=1&fm=Fira+Code&fs=14px&lh=133%25&si=false&es=4x&wm=false&code=from%2520pathlib%2520import%2520Path%250Aimport%2520matplotlib.pyplot%2520as%2520plt%250Aimport%2520pandas%2520as%2520pd%250A%250A%2523%2520...%2520code%2520for%2520setting%2520filepaths%2520...%250A%250Apil%2520%253D%2520pd.read_csv%28pil_file%252C%2520index_col%253D%2522Scenario%2522%29%250A%250A%2523%2520...%2520code%2520for%2520plot%2520style%2520%2526%2520labels%2520...%250A%250Afig%252C%2520axs%2520%253D%2520plt.subplots%281%252C%25202%252C%2520figsize%253D%2810%252C%25205%29%29%250A%250Apil.plot%28ax%253Daxs%255B1%255D%252C%2520legend%253DFalse%252C%2520color%253Dcolors%29%250A%250Aaxs%255B1%255D.set_title%28%2522Produzione%2520Interna%2520Lorda%2520a%2520livello%2520globale%2522%29%250Aaxs%255B1%255D.set_xlabel%28%2522Anno%2522%29%250Aaxs%255B1%255D.set_ylabel%28%2522PIL%2520%28mld%2520USD%252Fanno%29%2522%29%250A%250Aplt.show%28%29)