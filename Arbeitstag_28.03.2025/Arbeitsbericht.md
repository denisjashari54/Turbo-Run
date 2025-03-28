## Arbeitsbericht 28.03.2025

Wir haben heute unsere Laufplattform für den Endless Runner fertiggestellt. Sodass der Spielfluss möglichst glatt läuft, wird immer ein Chunk hinter dem Spieler gelöscht und ein Chunk vor dem Spieler hinzugefügt. Dabei hatten wir zu Beginn grosse Probleme, da die Laufplattform sich nicht ausweite und der Spieler nicht nach vorne lief, sondern non-stop auf den gleichen Punkt stand. Dies konnten wir mit MoveChunk() beheben, benötigten dabei die Hilfe von ChatGPT. Den Rest konnten wir problemlos implementieren. Zusätzlich fügten wir ein Design hinzu für die Laufplattform. Das ganze haben wir wieder im "LevelGenerator : MonoBehaviour" C# Skript implementiert.

Ziel für nächste Woche:
Die verlorene Zeit aufholen, sodass wir nicht unter Druck geraten, denn wie schon erwähnt, hat uns die Laufplattform für den heutigen Arbeitstag viel Zeit entnommen.



