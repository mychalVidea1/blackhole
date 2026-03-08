# 1. BlackHoleSim.html
Tato verze je zaměřená na uživatelskou interaktivitu a vizualizaci různých teoretických jevů. Obsahuje ovládací panel s experimenty pro testování chování hmoty v extrémní gravitaci.

Klíčové funkce:

Spaghettification Sim (Sonda): Vypuštění sondy, která padá k horizontu událostí, doprovázené vizualizací dilatace času a extrémního rudého posuvu (redshift).

Relativistické výtrysky (Jets): Možnost zažehnout plazmatické jety tryskající z pólů černé díry, simulující Blandfordův-Znajekův proces.

Fotonová past: Vystřelení testovacího světelného paprsku do nestabilní oběžné dráhy (fotonové sféry).

2K Tile Renderer: Záchyt snímků ve vysokém rozlišení. Využívá Temporal Anti-Aliasing (TAA) a rozděluje výpočet na větší dlaždice (128x128px), aby odlehčil grafické kartě.

Ovládání:
Táhnutí myší: Rotace kamery (Orbit)
Kolečko myši: Přiblížení / Oddálení (Zoom)
Mezerník: Vypuštění sondy
E: Aktivace polárních jetů (0.99c)
F: Vystřelení fotonu
P: Spuštění 4K renderu
Q / R: Náklon kamery (Roll)

# 2. BLACKHOLE SIM - CINEMATIC.html
Tato verze je ořezaná o dodatečné "herní" experimenty a plně se soustředí na vizuální čistotu a extrémně stabilní renderování velkých pláten. Je optimalizovaná pro tvorbu tapet a filmových snímků.

Klíčové funkce:

Adaptive Render Engine: Při pohybu kamerou se automaticky snižuje počet oktáv šumu pro zachování plynulého náhledu. Po zastavení se detaily opět zjemní.

Safe-Tile 4K Render: Upravený renderovací engine, který rozseká obraz na miniaturní dlaždice (8x8 pixelů). Ačkoliv export trvá déle, tento systém garantuje, že GPU nespadne na timeout (vyhne se chybě TDR v prohlížeči) i při enormním zatížení a rozlišení 4K.

Cinematic Grading: Přidaná chromatická aberace (rozklad barev na okrajích čočky) a odlesky objektivu aktivní výhradně během finálního renderu.

Ovládání:

Táhnutí myší: Rotace kamery
Kolečko myši: Přiblížení / Oddálení
Mezerník: Vypuštění sondy
P: Spuštění 2K "Deep Renderu"
