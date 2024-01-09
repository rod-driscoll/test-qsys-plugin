# test-qsys-plugin

Minimal qsys plugin to use as a scratchpad

# instructions

1. Copy the entire folders "Test-Module-CamelCase" and 'test-module-lowercase' into %USERPROFILE%\Documents\QSC\Q-Sys Designer\Modules
2. In Q-Sys Designer go to Tools > Show Design Resources... > install both modules
3. Copy 'camelcase-module-test.qplug' and 'lowercase-module-test.qplug' into %USERPROFILE%\Documents\QSC\Q-Sys Designer\Plugins
4. Open 'Plugin-with-modules-test.qsys'
5. In Q-Sys Designer go to Tools > Show Design Resources... > install both modules (they are in Schematic Elements > Plugins > User > Test Plugins)
6. Run the program in emulate mode, it will not error
7. run the program on a core, you will see the CamelCase module error
