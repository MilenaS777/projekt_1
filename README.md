1. Projekt Python akademie
Zadání projektu:
V tomto projektu bude tvým cílem vytvořit textový analyzátor - program, který se bude umět prokousat libovolně dlouhým textem a zjistit o něm různé informace.
Tvůj program bude obsahovat následující:
Vyžádá si od uživatele přihlašovací jméno a heslo, zjistí, jestli zadané údaje odpovídají někomu z registrovaných uživatelů, pokud je registrovaný, pozdrav jej a umožni mu analyzovat texty, pokud není registrovaný, upozorni jej a ukonči program.** Registrováni jsou následující uživatelé: bob, ann, mike, liz
Program nechá uživatele vybrat mezi třemi texty, uloženými v proměnné TEXTS:
Pokud uživatel vybere takové číslo textu, které není v zadání, program jej upozorní a skončí, pokud uživatel zadá jiný vstup než číslo, program jej rovněž upozorní a skončí.
Pro vybraný text spočítá následující statistiky:
počet slov, počet slov začínajících velkým písmenem, počet slov psaných velkými písmeny, počet slov psaných malými písmeny, počet čísel (ne cifer), sumu všech čísel (ne cifer) v textu.
Program zobrazí jednoduchý sloupcový graf, který bude reprezentovat četnost různých délek slov v textu. 

Tento program využívá ke své funkci knihovny Python: 
re ;
collections
a sys.
Program není omezen na přesně 3 texty (viz zadání), ale umí pracovat s lib. počtem textů.
