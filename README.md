Gustini Library: ConfigFileTool
======
** Tool to Read and Write INI-Configs to and from HashMaps

# Project was moved to consolidated Project https://github.com/rentasad/library_basicTools

## Usage

Example INI-File: config.ini
```
[MYSQL_DATABASE_CONNECTION]
MYSQL_HOST=hostname
MYSQL_DATABASE=database
MYSQL_USER=user
MYSQL_PASSWORD=password
```
###Example JavaCode read single Section from INI-File
```
String configFilePath = "config.ini";
String iniSection = "MYSQL_DATABASE_CONNECTION";

Map<String, String> mySqlConfigMap = ConfigFileTool.readConfiguration(configFilePath, iniSection);

```
