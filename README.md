# InkyPi-Plugin-PluginManager
![Example of InkyPi-Plugin-PluginManager](./example.png)

*InkyPi-Plugin-PluginManager* is a plugin for [InkyPi](https://github.com/fatihak/InkyPi) 

**What it does:**


## Installation

### Install

Install the plugin using the InkyPi CLI, providing the plugin ID and GitHub repository URL:

```bash
inkypi plugin install pluginmanager https://github.com/RobinWts/InkyPi-Plugin-PluginManager
```

After succesfull install you need to run the patch-script to patch the InkyPi core files for use of PluginManager, see [CORE_CHANGES.md](https://github.com/RobinWts/InkyPi-Plugin-PluginManager/blob/main/pluginmanager/CORE_CHANGES.md) for details:
```bash
bash src/plugins/pluginmanager/patch-core.sh
```
## Development-status

WIP

## License

This project is licensed under the GNU public License.
