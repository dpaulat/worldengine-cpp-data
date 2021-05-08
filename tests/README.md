To verify the drawing behaviors remain consistent, golden images are generated.  Tests verify generated images do not deviate from the golden set.

To generate the golden set, the following commands are used:
```
worldengine.exe --seed 1618 --width 300 --height 200 --rivers --grayscale-heightmap --scatter --sat --ice --world-map --elevation-map
worldengine.exe ancient_map seed_1618.world --resize-factor 3
```
