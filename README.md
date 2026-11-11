# w0dkaMP-launcher

Kanał aktualizacji **launchera** w0dkaMP (My Summer Car multiplayer).

Launcher sprawdza najnowsze wydanie w tym repozytorium i pobiera z niego instalator.

## Kontrakt wydania

| element | wartość |
|---|---|
| tag | `launcher-<wersja>` (np. `launcher-1.0.97.0`) |
| asset | `W0DKAMP-<wersja>-setup.exe` (np. `W0DKAMP-1.0.97-setup.exe`) |
| typ | release (nie draft, nie prerelease) |

Wersja w tagu musi odpowiadać wersji pliku `W0DKAMP.exe` (FileVersion `1.0.97.0`),
inaczej launcher odrzuci aktualizację.

## Jak zaktualizować

Launcher → zakładka **AKTUALIZACJE** → **POBIERZ AKTUALIZACJĘ**.
Launcher pobiera asset z najnowszego wydania, sprawdza sumę SHA256 i uruchamia
instalator bez okna.

## Kanał moda

Aktualizacja samego moda (`W0DKAMP.dll`) żyje osobno:
<https://github.com/gracz5769-arch/w0dkaMP-game>.
