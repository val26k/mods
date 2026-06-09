# SharedMapPins

Synchronizuje piny mapy miedzy graczami na serwerze, z ochrona przed duplikatami.

## Instalacja

1. Skopiuj folder `heatl-SharedMapPins` do `BepInEx/plugins/` na **serwerze i kazdym kliencie**.
2. W `eu.mydayyy.plugins.serversidemap.cfg` zostaw `EnableMarkerShare = false` (unikasz konfliktu z ServerSideMap).
3. Uruchom ponownie gre / serwer.

## Konfiguracja

Plik: `BepInEx/config/heatl.sharedmappins.cfg`

### [Server] — ustawienia serwera (autorytatywne)

Te wartosci sa **wysylane do klientow** przy polaczeniu. Klient nie moze ich nadpisac.


| Opcja                       | Domyslnie | Opis                                                                                                      |
| --------------------------- | --------- | --------------------------------------------------------------------------------------------------------- |
| `AllowPinSync`              | `true`    | Serwer zezwala na synchronizacje pinow. `false` = nikt nie moze syncowac, nawet jesli klient ma wlaczone. |
| `DuplicatePinRadius`        | `5`       | Promien deduplikacji (jednostki swiata).                                                                  |
| `MatchPinNameForDuplicates` | `true`    | Duplikat wymaga tej samej nazwy.                                                                          |


### [Client] — ustawienia klienta


| Opcja                  | Domyslnie | Opis                                                                                                           |
| ---------------------- | --------- | -------------------------------------------------------------------------------------------------------------- |
| `ParticipateInPinSync` | `true`    | Ten klient wysyla wlasne piny na serwer. Nadal **odbiera** piny innych, jesli serwer ma `AllowPinSync = true`. |


## Zachowanie

- **Serwer `AllowPinSync = false`** — brak syncu, klienci dostaja pusta liste pinow.
- **Klient `ParticipateInPinSync = false`** — nie wysyla wlasnych pinow, ale widzi piny innych.
- Ustawienia deduplikacji z sekcji `[Server]` sa synchronizowane do wszystkich klientow.

## Zrodla

```bash
dotnet build src/SharedMapPins/SharedMapPins.csproj -c Release
```

