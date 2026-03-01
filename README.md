# Reto_2
Este es mi asignacion de clases con respecto a un juego llamado valorant de la empresa riot games, hecho en Mermaid si ven algo que esta mal ojala me puedan avisar para cambiarlo muchas gracias (Corregido: mas simplificado con fin de ver bien las asignaciones)
En principio este es el codigo


	config:
  	theme: redux-dark
  	layout: elk
	---

	classDiagram
	direction TB
    class Valorant["PartidaValorant"] {
	    +Teclado
	    +Mouse
	    +Buen Internet
    }

    class Jugador {
	    +Manos
    }

    class ModosJuego {
	    +JuegoValorant
        +Ranked
        +Premier
        +Swiftplay
        +NoCompetitivo
        +TeamDM
        +SingleDM
        +SpikeRush
        +QuickMatch
        +Replica
        +Escaramusa
        +Escalation
    }

    class Agentes {
	    +JuegoValorant
    }

    class Controllers {
        +Habilidades
        -Control
        +Omen 
        +Clove
        +Brimstone
        +Harbor
        +Astra
        +Viper
    }

    class Duelists{
        +Habilidades
        -Entrar
        +Yoru
        +Jett
        +Phoenix
        +Raze
        +Neon
        +Reyna
        +Iso
        +Waylay
    }

    class Initiators{
        +Habilidades
        -AyudaEntrar
        +Kay_o
        +Sova
        +Skye
        +Fade
        +Geeko
        +Tejo
        +Breach
    }

    class Sentinels{
        +Habilidades
        -Proteger
        +Chamber
        +Killjoy
        +Deathlock
        +Cypher
        +Veto
        +Sage
        +Vyse
    }
    
    class Armas {
	    +JuegoValorant
        +Pistolas
        +Subfusiles
        +Escopetas
        +Rifles
        +Francotiradores
        +Pesadas
        +Cuchillo
    }

    class Servidores {
	    +JuegoValorant
        -Emparejamiento
        +SantiagoChile
        +Bogota
        +Miami
    }

    class Mapas {
	    +JuegoValorant
        +Sites
        +Corrode
        +Abyss
        +Sunset
        +Lotus
        +Pearl
        +Fracture
        +Breeze
        +Icebox
        +Ascent
        +Split
        +Haven
        +Bind
    }

    Jugador "10" --> "1" Valorant : Entrar partida()
    ModosJuego "10" --* "1" Valorant
    Agentes "28" --* "1" Valorant
    Agentes "28" ..> "1" ModosJuego
    Armas "18" --* "1" Valorant
    Armas "18" ..> "1" ModosJuego
    Servidores "3" --* "1" Valorant
    Mapas "12" --* "1" Valorant
    Mapas "12" ..> "1" ModosJuego
    Agentes <|-- Controllers
    Agentes <|-- Sentinels
    Agentes <|-- Duelists
    Agentes <|-- Initiators

Esta es la asignacion...
```mermaid
classDiagram
direction TB
    class Valorant["PartidaValorant"] {
	    +Teclado
	    +Mouse
	    +Buen Internet
    }

    class Jugador {
	    +Manos
    }

    class ModosJuego {
	    +JuegoValorant
        +Ranked
        +Premier
        +Swiftplay
        +NoCompetitivo
        +TeamDM
        +SingleDM
        +SpikeRush
        +QuickMatch
        +Replica
        +Escaramusa
        +Escalation
    }

    class Agentes {
	    +JuegoValorant
    }

    class Controllers {
        +Habilidades
        -Control
        +Omen 
        +Clove
        +Brimstone
        +Harbor
        +Astra
        +Viper
    }

    class Duelists{
        +Habilidades
        -Entrar
        +Yoru
        +Jett
        +Phoenix
        +Raze
        +Neon
        +Reyna
        +Iso
        +Waylay
    }

    class Initiators{
        +Habilidades
        -AyudaEntrar
        +Kay_o
        +Sova
        +Skye
        +Fade
        +Geeko
        +Tejo
        +Breach
    }

    class Sentinels{
        +Habilidades
        -Proteger
        +Chamber
        +Killjoy
        +Deathlock
        +Cypher
        +Veto
        +Sage
        +Vyse
    }
    
    class Armas {
	    +JuegoValorant
        +Pistolas
        +Subfusiles
        +Escopetas
        +Rifles
        +Francotiradores
        +Pesadas
        +Cuchillo
    }

    class Servidores {
	    +JuegoValorant
        -Emparejamiento
        +SantiagoChile
        +Bogota
        +Miami
    }

    class Mapas {
	    +JuegoValorant
        +Sites
        +Corrode
        +Abyss
        +Sunset
        +Lotus
        +Pearl
        +Fracture
        +Breeze
        +Icebox
        +Ascent
        +Split
        +Haven
        +Bind
    }

    Jugador "10" --> "1" Valorant : Entrar partida()
    ModosJuego "10" --* "1" Valorant
    Agentes "28" --* "1" Valorant
    Agentes "28" ..> "1" ModosJuego
    Armas "18" --* "1" Valorant
    Armas "18" ..> "1" ModosJuego
    Servidores "3" --* "1" Valorant
    Mapas "12" --* "1" Valorant
    Mapas "12" ..> "1" ModosJuego
    Agentes <|-- Controllers
    Agentes <|-- Sentinels
    Agentes <|-- Duelists
    Agentes <|-- Initiators
