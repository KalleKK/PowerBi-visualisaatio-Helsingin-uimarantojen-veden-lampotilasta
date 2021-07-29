# Visualisointi Helsingin uimarantojen veden ja ilman lämpötilasta

Tämä PowerBi Visualisointi on tehty hyödyntämällä avoindata.fi sivustolta löytyvää lähdettä nimeltä [Veden reaaliaikainen lämpötila Helsingin uimarannoilla](https://www.avoindata.fi/data/fi/dataset/veden-reaaliaikainen-lampotila-helsingin-uimarannoilla). Data päivittyy automaattisesti noin puolen tunnin välein, mutta joillakin rannoilla olevat mittarit päivittyvät useammin kuin muut. Hyödynsin Pythonia luodakseni koodin, joka puskee automaattisesti datan lähteestä SQL-tietokantaan, kahteen eri taulukkoon. Hyödynsin näitä kahta taulukkoa PowerBi visualisointia tehdessäni. PowerBi visualisointi päivittyy automaattisesti joka toinen tunti Power automaten avulla. Päivittyminen tarkoittaa, että PowerBi hakee visualisoinnissa käytettävän datan uudestaan SQL-taulukoista.

PowerBi visualisointi pysyy datan päivityksen ansiosta jokseenkin ajan tasalla automaattisesti.


Linkki PowerBi visualisointiin

https://app.powerbi.com/view?r=eyJrIjoiOTg5MTZiMTQtYzQ5OC00NmZhLTkxOTAtYzI4YmNiM2QyMjhhIiwidCI6ImM4NTBmZTljLWI0NmMtNGIyZC1iODYzLTAxZmEyYTg5ODA2OCIsImMiOjh9&pageName=ReportSection
