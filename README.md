# discover-lerna
try to figure out how Lerna does its version updates

1. **Lerna publish** is adding tags to the git repository
2. **Lerna changed** geeft geen output zonde **-a** (-a toont ook de private packages)
3. Om yarn workspaces te laten werken met Lerna moet je in .yarnrc *workspaces-experimental true* zetten
4. Als een file in een sub-workspace veranderd,wordt ook de versie van de parent workspace(s) opgehoogd  
