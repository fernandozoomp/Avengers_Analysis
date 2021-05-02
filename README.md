# Avengers_Analysis

### Análise do dataset sobre informações dos vingadores e suas participações no Universo Marvel das HQ's. Esta análise foi realizada em Python e para os Dashboards e Visualizações foi utilizado o Tableau Desktop.

Esta análise identifica e tras uma visão de fã sobre as mortes de Vingadores por trás das histórias. Mas não tema! Se há uma coisa que os fãs de quadrinhos aprenderam nos últimos 50 anos de Avengers, é que a morte é passageira.

Se você se inscreveu na equipe dos Vingadores, não apenas obtém um seguro de saúde fantástico, mas também, presumivelmente, consegue amigos que mudam a realidade para lidar com qualquer problema do tipo eliminar prematuramente algum problema.

Então, como definimos morte no Universo Marvel? Normalmente isso é muito simples, mas estamos falando de histórias em quadrinhos. 
Seguindo os critéiros das HQ's um personagem é considerado morto se:

* Eles aparecem mortos diretamente ou implícitamente é sugerido que estão mortos;

* E seus aliados e amigos mais próximos acreditam sinceramente que eles estão mortos.

O Dataset `avengers.csv`  foi obtido no site https://data.fivethirtyeight.com/ adapto para o português e detalha as mortes de personagens de quadrinhos da Marvel entre o momento em que se juntaram aos Vingadores e 30 de abril de 2015, uma semana antes das Guerras Secretas # 1.

Header | Definition
---|---------
`URL`| The URL of the comic character on the Marvel Wikia
`Name/Alias` | The full name or alias of the character
`Appearances` | The number of comic books that character appeared in as of April 30 
`Current?` | Is the member currently active on an avengers affiliated team?
`Gender` | The recorded gender of the character
`Probationary` | Sometimes the character was given probationary status as an Avenger, this is the date that happened
`Full/Reserve` | The month and year the character was introduced as a full or reserve member of the Avengers
`Year` | The year the character was introduced as a full or reserve member of the Avengers
`Years since joining` | 2015 minus the year
`Honorary` | The status of the avenger, if they were given "Honorary" Avenger status, if they are simply in the "Academy," or "Full" otherwise
`Death1` | Yes if the Avenger died, No if not. 
`Return1` | Yes if the Avenger returned from their first death, No if  they did not, blank if not applicable
`Death2` | Yes if the Avenger died a second time after their revival, No if they did not, blank if not applicable
`Return2` | Yes if the Avenger returned from their second death, No if they did not, blank if not applicable
`Death3` | Yes if the Avenger died a third time after their second revival, No if they did not, blank if not applicable
`Return3` | Yes if the Avenger returned from their third death, No if they did not, blank if not applicable
`Death4` | Yes if the Avenger died a fourth time after their third revival, No if they did not, blank if not applicable
`Return4` | Yes if the Avenger returned from their fourth death, No if they did not, blank if not applicable
`Death5` | Yes if the Avenger died a fifth time after their fourth revival, No if they did not, blank if not applicable
`Return5` | Yes if the Avenger returned from their fifth death, No if they did not, blank if not applicable
`Notes` | Descriptions of deaths and resurrections. 
