# Week09_BallsAndTheirAdmirers
Programmet skal, ved hjælp af raylib, genererer et vindue, 
hvor bolde med tilfældige farver genereres og bevæges rundt,
samtidig med at de samles. Der vælges en tilfældig "leder",
som andre bolde følger rundt.

# Krav
1. Hver bold har position baseret på pos_ , vel_ radius og color.
2. Hver bold starter et tilfældigt sted (rand() ).
3. Templaten er anvendt.
4. Et flowchart et inkluderet.
5. Raylib er ikke med i filerne
6. En demovideo er inkluderet.

# Generering af bolde
Boldene genereres med tilfældige hastigheder, farver og ledere (til at følge).
Dette opnås ved at hver parameter (posx/posy, velx/vely og color) tildeles med rand().

# Randomiseret opstart
For at sikre et tilfældigt seed ved hver opstart, så man ikke får den 
samme kørsel hver gang, anvendes srand() sammen med time(NULL) for 
at basere programmets seed på tid - som jo ændrer sig konstant.


# Filer
main.c                      - Selve programmet
README.md                   - Denne README.
ball_admirers_demo.mp4      - Demovideo af programmet
balls_atA_flow.svg          - Simpelt flowchart for programmet
compile_flags.txt
tasks.json
launch.json
.gitignore