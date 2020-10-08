# RWS Plugin Template
A template for RobWorkStudio plugins. For personal use.

## Usage
After compiling, the plugin will be in ``./libs/``. 
Do not edit the ``RobWorkStudio.ini`` in the workcell directory.
Instead, either run ``./workcell/generate_ini.sh`` to generate the init file
with absolute path to plugin. Alternately, run ``./start.sh`` to automatically
generate the init file, run RobWorkStudio, and load selected Workcell and 
plugin. Make both scripts executable (``chmod +x``) as needed.

## QtCreator
In order for it to work smoothly with QtCreator, go to 
``Project > Build & Run > Run`` and specify the following:

| Exectuable | %{sourceDir}/start.sh |
| Working directory | %{sourceDir} |
