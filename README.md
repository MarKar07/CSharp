# Tekstiseikkailupeli englanniksi

## Sovelluksen toiminta ja käyttötarkoitus
Tämä tekstiseikkailu on konsolipohjainen roolipeli, jossa pelaaja tutkii vanhaa linnaa. Pelaaja voi liikkua huoneesta toiseen, löytää esineitä, kerätä kultaa ja lopulta paeta linnasta. Pelin tarkoitus on viihdyttää ja tarjota interaktiivinen tarinakokemus.

## Sovelluksen vuokaavio
[Lisää kuva vuokaaviosta tähän]

## Kuvakaappaukset sovelluksesta
[Lisää kuvakaappauksia tähän]

## Koodin pääkohdat

### Player-luokka
Hallinnoi pelaajan tietoja kuten terveyttä, kultaa ja tavaraluetteloa.

```csharp
public class Player
{
    public int Health { get; set; }
    public int Gold { get; set; }
    public List<Item> Inventory { get; set; }
    public string CurrentLocation { get; set; }
    
    // Metodeita pelaajan toimintoihin...
}

public class Game
{
    // Pelin käynnistys ja hallinta...
    
    // Tallennusjärjestelmä...
    
    // Huoneet ja siirtymät...
}
