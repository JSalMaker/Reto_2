# Reto_2
Este es mi asignacion de clases con respecto a un juego llamado valorant de la empresa riot games, hecho en Mermaid si ven algo que esta mal ojala me puedan avisar para cambiarlo muchas gracias
Pegarlo tal cual para Verlo bien en Mermaid

Copie apartir de "---"
```mermaid
---
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
    }

    class Agentes {
	    +JuegoValorant
    }

    class Controllers {
        +Habilidades
        +Control
    }

    class Omen {
        +Habilidades
        +Control
    }

    class Clove{
        +Habilidades
        +Control
    }

    class Brimstone{
        +Habilidades
        +Control
    }

    class Harbor{
        +Habilidades
        +Control
    }

    class Astra{
        +Habilidades
        +Control
    }

    class Viper{
        +Habilidades
        +Control
    }

    class Duelists{
        +Habilidades
        +Entrar
    }

    class Yoru{
        +Habilidades
        +Entrar
    }

    class Jett{
        +Habilidades
        +Entrar
    }

    class Phoenix{
        +Habilidades
        +Entrar
    }

    class Raze{
        +Habilidades
        +Entrar
    }

    class Neon{
        +Habilidades
        +Entrar
    }

    class Reyna{
        +Habilidades
        +Entrar
    }

    class Waylay {
        +Habilidades
        +Entrar
    }
    
    class Iso{
        +Habilidades
        +Entrar
    }

    class Initiators{
        +Habilidades
        +AyudaEntrar
    }

    class Kay_o{
        +Habilidades
        +AyudaEntrar
    }

    class Sova{
        +Habilidades
        +AyudaEntrar
    }

    class Skye{
        +Habilidades
        +AyudaEntrar
    }

    class Fade{
        +Habilidades
        +AyudaEntrar
    }

    class Geeko{
        +Habilidades
        +AyudaEntrar
    }

    class Tejo{
        +Habilidades
        +AyudaEntrar
    }

    class Breach{
        +Habilidades
        +AyudaEntrar
    }

    class Sentinels{
        +Habilidades
        +Proteger
    }

    class Chamber{
        +Habilidades
        +Proteger
    }

    class Killjoy{
        +Habilidades
        +Proteger
    }

    class Deathlock{
        +Habilidades
        +Proteger
    }

    class Cypher{
        +Habilidades
        +Proteger
    }

    class Sage{
        +Habilidades
        +Proteger
    }

    class Vyse{
        +Habilidades
        +Proteger
    }
    
    class Veto{
        +Habilidades
        +Proteger
    }
    
    class Armas {
	    +JuegoValorant
    }

    class Pistolas{
        +PocoCosto
        +PocasBalas
        +DistanciaCorta
    }

    class Classic{
        +PocoCosto
        +PocasBalas
        +DistanciaCorta
    }

    class Frenzy{
        +PocoCosto
        +PocasBalas
        +DistanciaCorta
    }

    class Shorty{
        +PocoCosto
        +PocasBalas
        +DistanciaCorta
    }

    class Ghost{
        +PocoCosto
        +PocasBalas
        +DistanciaCorta
    }

    class Sheriff{
        +PocoCosto
        +PocasBalas
        +DistanciaCorta
    }

    class Subfusiles{
        +PocoCosto
        +MuchasBalas
        +DistanciaCorta
    }

    class Stinger{
        +PocoCosto
        +MuchasBalas
        +DistanciaCorta
    }

    class Spectre {
        +PocoCosto
        +MuchasBalas
        +DistanciaCorta
    }

    class Escopetas{
        +PocoCosto
        +PocasBalas
        +DistanciaCorta
    }

    class Judge{
        +PocoCosto
        +PocasBalas
        +DistanciaCorta
    }

    class Bucky{
        +PocoCosto
        +PocasBalas
        +DistanciaCorta
    }

    class Rifles{
        +CostoMedio
        +MuchasBalas
        +DistanciaLarga
    }

    class Bulldog{
        +CostoMedio
        +MuchasBalas
        +DistanciaLarga
    }

    class Guardian{
        +CostoMedio
        +MuchasBalas
        +DistanciaLarga
    }

    class Vandal{
        +CostoMedio
        +MuchasBalas
        +DistanciaLarga
    }

    class Phanthom{
        +CostoMedio
        +MuchasBalas
        +DistanciaLarga
    }

    class Francotiradores{
        +CostoElevado
        +PocasBalas
        +DistanciaLarga
    }

    class Outlaw{
        +CostoElevado
        +PocasBalas
        +DistanciaLarga
    }

    class Marshal{
        +CostoElevado
        +PocasBalas
        +DistanciaLarga
    }

    class Operator{
        +CostoElevado
        +PocasBalas
        +DistanciaLarga
    }

    class Pesadas{
        +CostoElevado
        +MuchasBalas
        +DistanciaMedia
    }

    class Odin{
        +CostoElevado
        +MuchasBalas
        +DistanciaMedia
    }

    class Ares{
        +CostoElevado
        +MuchasBalas
        +DistanciaMedia
    }
    
    class Cuchillo{
        +Gratis
        +DistanciaCorta
    }
    class Servidores {
	    +JuegoValorant
        -Emparejamiento
    }

    class SantiagoChile{
        +JuegoValorant
        -Emparejamiento
    }

    class Bogota{
        +JuegoValorant
        -Emparejamiento
    }

    class Miami{
        +JuegoValorant
        -Emparejamiento
    }

    class Mapas {
	    +JuegoValorant
        +Sites
    }

    class Corrode {
        +SiteA
        +SiteB
        +Mid()
        +ZonaATT
        +ZonaDEF        
    }
    class Abyss {
        +SiteA
        +SiteB
        +Mid()
        +ZonaATT
        +ZonaDEF
    }

    class Sunset{
        +SiteA
        +SiteB
        +Mid()
        +ZonaATT
        +ZonaDEF
    }
    
    class Lotus{
        +SiteA
        +SiteB
        +SiteC
        +ZonaATT
        +ZonaDEF
    }

    class Pearl {
        +SiteA
        +SiteB
        +MidA
        +MidB
        +ZonaATT
        +ZonaDEF
    }

    class Fracture{
        +SiteA
        +SiteB
        +Mid()
        +ZonaATT
        +ZonaDEF
    }

    class Breeze {
        +SiteA
        +SiteB
        +Mid()
        +ZonaATT
        +ZonaDEF
    }

    class Icebox {
        +SiteA
        +SiteB
        +Mid()
        +ZonaATT
        +ZonaDEF
    }

    class Ascent{
        +SiteA
        +SiteB
        +Mid()
        +ZonaATT
        +ZonaDEF
    }

    class Split{
        +SiteA
        +SiteB
        +Mid()
        +ZonaATT
        +ZonaDEF
    }

    class Haven{
        +SiteA
        +SiteB
        +SiteC
        +ZonaATT
        +ZonaDEF
    }

    class Bind{
        +SiteA
        +SiteB
        +Mid()
        +ZonaATT
        +ZonaDEF
    }

    class Competitivo {
	    +Ligas
	    +MMR
	    -Emparejamiento
    }

    class Rankeds {
	    +MMR
	    +Competitivo
	    -Emparejamiento
    }

    class Hierro {
	    +MMR
	    -Emparejamiento
    }

    class Bronce {
	    +MMR
	    -Emparejamiento
    }

    class PLata {
	    +MMR
	    -Emparejamiento
    }

    class Oro {
	    +MMR
	    -Emparejamiento
    }

    class Platino {
	    +MMR
	    -Emparejamiento
    }

    class Diamante {
	    +MMR
	    -Emparejamiento
    }

    class Acendente {
	    +MMR
	    -Emparejamiento
    }

    class Inmortal {
	    +MMR
	    -Emparejamiento
    }

    class Radiante {
	    +MMR
	    -Emparejamiento
    }

    class Premier {
    }

    class Abierto {
	    +MMR
	    -Emparejamiento
    }

    class Intermedio {
	    +MMR
        -Emparejamiento
    }

    class Avanzada {
        +MMR
        -Emparejamiento
    }

    class Elite {
        +MMR
        -Emparejamiento
    }

    class Contendiente {
        +MMR
        -Emparejamiento
    }

    class Invitacion {
        +MMR
        -Emparejamiento
    }

    class Swiftplay {
        +MenosRondas
        +ModosInteractivos
    }

    class Nocompetitivo {
        +PartidaValorant
    }

    class Deathmatch {
        +SinHabilidades
        +CualquierArma
        +ContadorKill
    }

    class TeamDM {
        +MapasExclusivos
        +ContadorKill
        +SinHabilidades
        +CualquierArma
    }

    class SingleDM {
        +ContadorKill
        +SinHabilidades
        +CualquierArma
    }

    class SpikeRush {
        +MenosRondas
        +NoEleccionArmas
    }

    class QuickMatch {
        +MenosRondas
    }

    class Replica {
        +MenosRondas
        +MismoAgente
    }

    class Escaramusa {
        +MenosRondas
        +Menoshabilidades
        -TiempoLimitado
    }

    class Escalation {
        +MenosRondas
        +TodosMismaArma
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
    ModosJuego <|-- Competitivo
    Competitivo <|-- Rankeds
    Rankeds <|-- Hierro
    Rankeds <|-- Bronce
    Rankeds <|-- PLata
    Rankeds <|-- Oro
    Rankeds <|-- Platino
    Rankeds <|-- Diamante
    Rankeds <|-- Acendente
    Rankeds <|-- Inmortal
    Rankeds <|-- Radiante
    Competitivo <|-- Premier
    Premier <|-- Abierto
    Premier <|-- Intermedio
    Premier <|-- Avanzada
    Premier <|-- Elite
    Premier <|-- Contendiente
    Premier <|-- Invitacion
    ModosJuego <|-- Swiftplay
    ModosJuego <|-- Nocompetitivo
    ModosJuego <|-- Deathmatch
    Swiftplay <|-- SpikeRush
    Swiftplay <|-- QuickMatch
    Swiftplay <|-- Escalation
    Swiftplay <|-- Replica
    Swiftplay <|-- Escaramusa
    Deathmatch <|-- TeamDM
    Deathmatch <|-- SingleDM
    Servidores <|-- SantiagoChile
    Servidores <|-- Bogota
    Servidores <|-- Miami
    Agentes <|-- Controllers
    Agentes <|-- Sentinels
    Agentes <|-- Duelists
    Agentes <|-- Initiators
    Controllers <|-- Omen
    Controllers <|-- Astra
    Controllers <|-- Brimstone
    Controllers <|-- Harbor
    Controllers <|-- Viper
    Controllers <|-- Clove
    Sentinels <|-- Killjoy
    Sentinels <|-- Chamber
    Sentinels <|-- Cypher
    Sentinels <|-- Sage
    Sentinels <|-- Vyse
    Sentinels <|-- Deathlock
    Sentinels <|-- Veto
    Initiators <|-- Geeko
    Initiators <|-- Fade
    Initiators <|-- Sova
    Initiators <|-- Breach
    Initiators <|-- Kay_o
    Initiators <|-- Skye
    Initiators <|-- Tejo
    Duelists <|-- Reyna
    Duelists <|-- Yoru
    Duelists <|-- Raze
    Duelists <|-- Waylay
    Duelists <|-- Jett
    Duelists <|-- Phoenix
    Duelists <|-- Iso
    Duelists <|-- Neon
    Mapas <|-- Corrode
    Mapas <|-- Abyss
    Mapas <|-- Lotus
    Mapas <|-- Sunset
    Mapas <|-- Pearl
    Mapas <|-- Fracture
    Mapas <|-- Breeze
    Mapas <|-- Icebox
    Mapas <|-- Ascent
    Mapas <|-- Split
    Mapas <|-- Haven
    Mapas <|-- Bind
    Armas <|-- Pistolas
    Armas <|-- Subfusiles
    Armas <|-- Escopetas
    Armas <|-- Rifles
    Armas <|-- Francotiradores
    Armas <|-- Pesadas
    Armas <|-- Cuchillo
    Pistolas <|-- Classic
    Pistolas <|-- Sheriff
    Pistolas <|-- Frenzy
    Pistolas <|-- Shorty
    Pistolas <|-- Ghost
    Escopetas <|-- Judge
    Escopetas <|-- Bucky
    Rifles <|-- Vandal
    Rifles <|-- Guardian 
    Rifles <|-- Phanthom
    Rifles <|-- Bulldog
    Francotiradores <|-- Operator
    Francotiradores <|-- Outlaw
    Francotiradores <|-- Marshal
    Pesadas <|-- Odin 
    Pesadas <|-- Ares
    Subfusiles <|-- Stinger
    Subfusiles <|-- Spectre
