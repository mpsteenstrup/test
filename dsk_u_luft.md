Simulering af det skrå kast uden luftmodstand.

Hvis vi ser bort fra luftmodstanden er det kun tyngdekraften som virker på vores bold.

Newtons anden lov siger at $$\vec{F}=m\cdot \vec{a}$$, hvor F er kraften i newton, N, m er massen i kg og a er accelerationen.
Her skal vi bruge tyngdekraften som i nærheden af Jorden er $$ \vec{F}_T = m\cdot \vec{g}$$ hvor $$\vec{g} = (0,-9,82,0)\text{m/s}^2$$ er tyngdeaccelerationen pegenden nedad, -y retningen. 

Hvis vi sætter $$\vec{F}=\vec{F}_T$$ får vi $$m\cdot \vec{a} = m\cdot \vec{g}$$ eller at accelerationen bliver $$ \vec{a} = \vec{g} $$ og det er jo derfor at g har navnet tyngdeaccelerationen.

senariet er at bolden bliver sendt afsted med begyndelsesfarten v0 i en vinkel. Det giver hastighedsvektoren
$$
\vec{v} = (cos(vinek),sin(vinkel),0)\cdot v0
$$

<iframe src='https://trinket.io/embed/glowscript/a84c0a7a1c?toggleCode=true' width='100%' height='400' frameborder='0' marginwidth='0' marginheight='0' allowfullscreen></iframe>

* Kør simuleringen.
* Lav om på vinklen og se bevægelsen.
* Undersøg om 45 grader giver det længste kast.