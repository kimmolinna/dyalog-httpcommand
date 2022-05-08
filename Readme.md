## Unclassified HttpCommand
### Basic Usage
```apl
 hc←#.HttpCommand
 hc.init
 hc.(Command URL)←'get'url
 h←hc.Run
```