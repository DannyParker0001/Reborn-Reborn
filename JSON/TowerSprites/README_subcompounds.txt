Run this in the TowerSprites directory to get a hackish list of sub-compounds:

find . -not -name "Towers.json*" -not -name ".*" -maxdepth 1 -exec cat {} \; | grep ".json"