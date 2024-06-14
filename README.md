Zig bindings for Reaper DAW API

reaper_functions.zig can be used as is in your project

To generate bindings from python script you need:
1. pip install libclang
2. Reaper SDK - https://github.com/justinfrankel/reaper-sdk
3. WDL - https://github.com/justinfrankel/WDL
4. Copy binding generator script inside sdk/ folder
5. run python3 binding_generator.py
6. new reaper_functions.zig will be generated
