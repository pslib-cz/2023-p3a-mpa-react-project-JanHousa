# City Sprint

## Téma

City Sprint je rychlá strategická hra pro jednoho hráče, zaměřená na budování a správu města v omezeném časovém rámci. Hráč musí efektivně spravovat zdroje, rozvíjet infrastrukturu a zajišťovat potřeby obyvatelstva, aby udržel své město šťastné a prosperující. Hra končí, pokud populace města je nespokojená, svrhne vládu, nebo pokud obyvatelé umírají na hlad nebo nemoci.

Základní Mechaniky:

- Časový Limit: Hráč má omezený čas na dosažení co nejlepšího skóre. Čas může být prodloužen dosažením určitých cílů.
- Správa Zdrojů: Zdroje jako jsou voda, jídlo, a energie jsou klíčové pro přežití města. Je nutné je správně distribuovat.
- Stavba a Rozvoj: Hráč musí budovat a vylepšovat budovy jako domy, nemocnice, školy a infrastrukturu (cesty, veřejnou dopravu).
- Populace: Obyvatelstvo města se časem zvyšuje. Je třeba zajišťovat jejich potřeby a spokojenost.
- Náhodné Události: Hráč čelí náhodným událostem, jako jsou přírodní katastrofy, epidemie, nebo ekonomické krize, které ovlivňují chod města.

## Odkazy pro vývoj

Zde budou živé linky na:
https://www.figma.com/file/05MurFodwVQCbS7iW12B7Z/Untitled?type=design&node-id=0%3A1&mode=design&t=LjdZS9kZygTkkAZP-1

### Z čeho čerpat

- interaktivní hra (předělávka "deskovky")
- mohlo by být použitelné jako solitaire
- nebo "AI" protihráč
- inspirovat se můžete na [zatrolených hrách](https://www.zatrolene-hry.cz/katalog-her/?fType=cat&keyword=&theme=-1&category=-1&minlength=-1&maxlength=-1&localization=6%2C+7%2C+8&min_players=1&max_players=1&age=-1)...
- karetní hry méně typické - např. [Kabo](https://www.zatrolene-hry.cz/spolecenska-hra/kabo-8341/)
- učitelem oblíbená [Cartagena](https://www.zatrolene-hry.cz/spolecenska-hra/cartagena-422/) stále čeká na remake

### Techniky

- využití localStorage / sessionStorage
- čtení dat z externího RestAPI (fetch)
- operace DnD
- využití react-routeru
- funkčnost na mobilu (výjimka je předělávka komplexních deskových her)

### Co není obsahem 

- databáze
- bez vlastních backend service
- trapné věci: *klasické karetní hry*, *člověče nezlob se*, ...
