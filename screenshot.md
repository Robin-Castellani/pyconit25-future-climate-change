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

[Population raw](https://carbon.now.sh/?bg=rgba%28171%2C195%2C172%2C1%29&t=night-owl&wt=bw&l=python&width=714.25&ds=true&dsyoff=23px&dsblur=68px&wc=true&wa=true&pv=22px&ph=29px&ln=true&fl=1&fm=Fira+Code&fs=18px&lh=141%25&si=false&es=4x&wm=false&code=import%2520pyam%250A%250Aconnection_name%2520%253D%2520%2522ssp%2522%250Aconn%2520%253D%2520pyam.iiasa.Connection%28connection_name%29%250A%250Amodel%2520%253D%2520%2522IIASA-WiC%2520POP%25202023%2522%250Avariable%2520%253D%2520%2522Population%2522%250Aregion%2520%253D%2520%2522World%2522%250Ascenario%2520%253D%2520%255B%2522SSP1%2522%252C%2520%2522SSP2%2522%252C%2520%2522SSP3%2522%252C%2520%2522SSP4%2522%252C%2520%2522SSP5%2522%255D%250A%250Araw_population%2520%253D%2520conn.query%28%250A%2520%2520%2520%2520variable%253Dvariable%252C%250A%2520%2520%2520%2520model%253Dmodel%252C%250A%2520%2520%2520%2520scenario%253Dscenario%252C%250A%2520%2520%2520%2520region%253Dregion%252C%250A%29.as_pandas%28%29)

[Population plot](https://carbon.now.sh/?bg=rgba%28171%2C195%2C172%2C1%29&t=night-owl&wt=bw&l=python&width=714.25&ds=true&dsyoff=23px&dsblur=68px&wc=true&wa=true&pv=22px&ph=29px&ln=true&fl=1&fm=Fira+Code&fs=18px&lh=141%25&si=false&es=4x&wm=false&code=import%2520matplotlib.pyplot%2520as%2520plt%250A%250Afig%252C%2520axs%2520%253D%2520plt.subplots%281%252C%25202%252C%2520figsize%253D%2810%252C%25205%29%29%250A%250Apopulation.plot%28ax%253Daxs%255B0%255D%29%250A%250Aaxs%255B0%255D.set_title%28%2522Popolazione%2520mondiale%2522%29%250Aaxs%255B0%255D.set_xlabel%28%2522Anno%2522%29%250Aaxs%255B0%255D.set_ylabel%28%2522Popolazione%2520%28mld%2520persone%29%2522%29%250A%250Aplt.show%28%29)

[PIL raw](https://carbon.now.sh/?bg=rgba%28171%2C195%2C172%2C1%29&t=night-owl&wt=bw&l=python&width=714.25&ds=true&dsyoff=23px&dsblur=68px&wc=true&wa=true&pv=22px&ph=29px&ln=true&fl=1&fm=Fira+Code&fs=18px&lh=141%25&si=false&es=4x&wm=false&code=import%2520pyam%250A%250Aconnection_name%2520%253D%2520%2522ssp%2522%250Aconn%2520%253D%2520pyam.iiasa.Connection%28connection_name%29%250A%250Amodel%2520%253D%2520%2522IIASA%2520GDP%25202023%2522%250Avariable%2520%253D%2520%2522Population%2522%250Aregion%2520%253D%2520%2522World%2522%250Ascenario%2520%253D%2520%255B%2522SSP1%2522%252C%2520%2522SSP2%2522%252C%2520%2522SSP3%2522%252C%2520%2522SSP4%2522%252C%2520%2522SSP5%2522%255D%250A%250Araw_gdp%2520%253D%2520conn.query%28%250A%2520%2520%2520%2520variable%253Dvariable%252C%250A%2520%2520%2520%2520model%253Dmodel%252C%250A%2520%2520%2520%2520scenario%253Dscenario%252C%250A%2520%2520%2520%2520region%253Dregion%252C%250A%29.as_pandas%28%29)

[PIL plot](https://carbon.now.sh/?bg=rgba%28171%2C195%2C172%2C1%29&t=night-owl&wt=bw&l=python&width=1000&ds=true&dsyoff=23px&dsblur=68px&wc=true&wa=true&pv=22px&ph=29px&ln=true&fl=1&fm=Fira+Code&fs=18px&lh=141%25&si=false&es=4x&wm=false&code=pil.plot%28ax%253Daxs%255B1%255D%29%250A%250Aaxs%255B1%255D.set_title%28%2522Produzione%2520Interna%2520Lorda%2520a%2520livello%2520globale%2522%29%250Aaxs%255B1%255D.set_xlabel%28%2522Anno%2522%29%250Aaxs%255B1%255D.set_ylabel%28%2522PIL%2520%28trilioni%2520USD%252Fanno%29%2522%29%250A%250Aplt.show%28%29)

[Temp CO2 raw](https://carbon.now.sh/?bg=rgba%28171%2C195%2C172%2C1%29&t=night-owl&wt=bw&l=python&width=714.25&ds=true&dsyoff=23px&dsblur=68px&wc=true&wa=true&pv=22px&ph=29px&ln=true&fl=1&fm=Fira+Code&fs=18px&lh=141%25&si=false&es=4x&wm=false&code=import%2520io%250Aimport%2520pandas%2520as%2520pd%250Aimport%2520requests%250A%250Adata_url%2520%253D%2520%2522https%253A%252F%252Fraw.githubusercontent.com%252Fowid%252Fco2-data%252Fmaster%252Fowid-co2-data.csv%2522%250Aresponse%2520%253D%2520requests.get%28data_url%29%250Araw_data%2520%253D%2520pd.read_csv%28%250A%2520%2520%2520%2520io.BytesIO%28response.content%29%252C%250A%2520%2520%2520%2520index_col%253DFalse%252C%250A%2520%2520%2520%2520header%253D0%252C%250A%29)

[CMIP6 function](https://carbon.now.sh/?bg=rgba%28171%2C195%2C172%2C1%29&t=night-owl&wt=bw&l=python&width=714.25&ds=true&dsyoff=23px&dsblur=68px&wc=true&wa=true&pv=22px&ph=29px&ln=true&fl=1&fm=Fira+Code&fs=18px&lh=141%25&si=false&es=4x&wm=false&code=from%2520pathlib%2520import%2520Path%250Aimport%2520cdsapi%250A%250Adef%2520fetch_cmip6_data%28scenario%253A%2520str%252C%2520output_folder%253A%2520Path%29%2520-%253E%2520Path%253A%250A%2509client%2520%253D%2520cdsapi.Client%28%29%250A%2520%2520%2520%2520dataset%2520%253D%2520%2522projections-cmip6%2522%250A%2520%2520%2520%2520%250A%2520%2520%2520%2520match%2520scenario%253A%250A%2520%2520%2520%2520%2520%2520%2520%2520case%2520%2522historical%2522%253A%250A%2520%2520%2520%2520%2520%2520%2520%2520%2520%2520%2520%2520years%2520%253D%2520list%28str%28year%29%2520for%2520year%2520in%2520range%281950%252C%25202015%29%29%250A%2520%2520%2520%2520%2520%2520%2520%2520case%2520%2522ssp1_2_6%2522%2520%257C%2520%2522ssp2_4_5%2522%2520%257C%2520%2522ssp3_7_0%2522%2520%257C%2520%2522ssp4_6_0%2522%2520%257C%2520%2522ssp5_8_5%2522%253A%250A%2520%2520%2520%2520%2520%2520%2520%2520%2520%2520%2520%2520years%2520%253D%2520list%28str%28year%29%2520for%2520year%2520in%2520range%282015%252C%25202100%29%29%250A%250A%2520%2520%2520%2520request%2520%253D%2520%257B%250A%2520%2520%2520%2520%2520%2520%2520%2520%2522temporal_resolution%2522%253A%2520%2522monthly%2522%252C%250A%2520%2520%2520%2520%2520%2520%2520%2520%2522experiment%2522%253A%2520scenario%252C%250A%2520%2520%2520%2520%2520%2520%2520%2520%2522variable%2522%253A%2520%2522surface_temperature%2522%252C%2520%2520%2523%2520%25F0%259F%2594%25A5%2520%25E2%259D%2584%25EF%25B8%258F%250A%2520%2520%2520%2520%2520%2520%2520%2520%2522model%2522%253A%2520%2522mri_esm2_0%2522%252C%2520%2520%2523%2520a%2520model%2520among%2520many%250A%2520%2520%2520%2520%2520%2520%2520%2520%2522month%2522%253A%2520list%28f%2522%257Bmonth%253A02d%257D%2522%2520for%2520month%2520in%2520range%281%252C%252013%29%29%252C%250A%2520%2520%2520%2520%2520%2520%2520%2520%2522year%2522%253A%2520years%252C%250A%2520%2520%2520%2520%2520%2520%2520%2520%2522area%2522%253A%2520%255B47%252C%25205%252C%252035%252C%252020%255D%252C%2520%2520%2523%2520Italy%250A%2520%2520%2520%2520%257D%250A%2520%2520%2520%2520output_filepath%2520%253D%2520output_folder%2520%252F%2520f%2522%257Bscenario%257D.nc%2522%250A%250A%2520%2520%2520%2520client.retrieve%28dataset%252C%2520request%29.download%28output_filepath%29%250A%250A%2520%2520%2520%2520return%2520output_filepath)

[CMIP6 download](https://carbon.now.sh/?bg=rgba%28171%2C195%2C172%2C1%29&t=night-owl&wt=bw&l=python&width=714.25&ds=true&dsyoff=23px&dsblur=68px&wc=true&wa=true&pv=22px&ph=29px&ln=true&fl=1&fm=Fira+Code&fs=18px&lh=141%25&si=false&es=4x&wm=false&code=%2523%2520beware%252C%2520it%2520can%2520take%2520some%2520minutes%21%250Anc_filepaths%2520%253D%2520%257B%257D%250A%250Ascenarios%2520%253D%2520%255B%250A%2520%2520%2520%2520%2522historical%2522%252C%250A%2520%2520%2520%2520%2522ssp1_2_6%2522%252C%2520%2520%2523%2520sviluppo%2520sostenibile%250A%2520%2520%2520%2520%2522ssp2_4_5%2522%252C%2520%2520%2523%2520met%25C3%25A0%2520strada%250A%2520%2520%2520%2520%2522ssp3_7_0%2522%252C%2520%2520%2523%2520rivalit%25C3%25A0%2520regionali%250A%2520%2520%2520%2520%2522ssp4_6_0%2522%252C%2520%2520%2523%2520diseguaglianza%250A%2520%2520%2520%2520%2522ssp5_8_5%2522%252C%2520%2520%2523%2520sviluppo%2520basato%2520sui%2520comb.%2520foss.%250A%255D%250A%250Afor%2520scenario%2520in%2520scenarios%253A%250A%2520%2520%2520%2520nc_filepaths%255Bscenario%255D%2520%253D%2520fetch_cmip6_data%28%250A%2520%2520%2520%2520%2520%2520%2509scenario%252C%250A%2520%2520%2520%2520%2509output_folder%2520%253D%2520NETCDF_FOLDER%250A%2520%2520%2520%2520%29)

[Temperature first](https://carbon.now.sh/?bg=rgba%28171%2C195%2C172%2C1%29&t=night-owl&wt=bw&l=python&width=1000&ds=true&dsyoff=23px&dsblur=68px&wc=true&wa=true&pv=22px&ph=29px&ln=true&fl=1&fm=Fira+Code&fs=18px&lh=141%25&si=false&es=4x&wm=false&code=import%2520xarray%2520as%2520xr%250A%250Ads_svilsost%2520%253D%2520xr.open_dataset%28nc_filepaths%255B%2522ssp1_2_6%2522%255D%29%250Ada_svilsost%2520%253D%2520ds_svilsost.ts%250Ada_svilsost%2520%253D%2520da_svilsost.groupby%28%2522time.year%2522%29.mean%28%29%250Ada_svilsost%2520%253D%2520da_svilsost%2520-%2520273.15%2520%2520%2523%2520kelvin%2520to%2520celsius%250A%250Ada_svilsost.sel%28year%253D2025%29.plot%28%29)

[Temperature second](https://carbon.now.sh/?bg=rgba%28171%2C195%2C172%2C1%29&t=night-owl&wt=bw&l=python&width=1000&ds=true&dsyoff=23px&dsblur=68px&wc=true&wa=true&pv=22px&ph=29px&ln=true&fl=1&fm=Fira+Code&fs=18px&lh=141%25&si=false&es=4x&wm=false&code=import%2520geopandas%2520as%2520gpd%250A%250Amediterranean_countries%2520%253D%2520gpd.read_file%28med_countries_vectorial%29%250A%250Afig%252C%2520ax%2520%253D%2520plt.subplots%28figsize%253D%285%252C%25205%29%29%250Amediterranean.plot%28ax%253Dax%252C%2520color%253D%2522black%2522%252C%2520zorder%253D5%252C%2520linewidth%253D0.5%29%250Ada_svilsost.sel%28year%253D2025%29.plot%28ax%253Dax%252C%2520cmap%253D%2522Reds%2522%29)
