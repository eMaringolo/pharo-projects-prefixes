## Description
Collection of Pharo class prefixes for recognized public libraries/frameworks

## Rationale
Due to the lack of namespaces in [Pharo](https://pharo.org), the community has chosen to prefix class names (or even selectors) with a project-specific prefix to avoid class name clashing. 

## Purpose
The purpose of this list is to provide a public reference of such prefixes that works as a reference catalog, in order to avoid prefix clashing as well.

## List of prefixes

| Class name prefix | Selector prefix | Project name | Sample class name | Project/Repository URI | Other |
| ----------------- | --------------- | ------------ | ----------------- | ---------------------- | ----- |
| `Bl` | | Bloc | `BlElement` | https://github.com/pharo-graphics/Bloc | |
| `FAMIX` | | Famix (Moose) | `FAMIXType` | https://github.com/moosetechnology/Moose | |
| `FT` | | FastTable | `FTTableMorph` | | |
| `Gr` | | Grease Portability Library | `GRPlatform` | 
| `GT` | `#gt` | Glamourous Toolkit | `GTPlayground` | https://github.com/feenkcom/gtoolkit | |
| `Ice` | | Iceberg | `IceRepository` | https://github.com/pharo-vcs/iceberg | |
| `PM` | | PolyMath | `PMMatrix` | https://github.com/PolyMathOrg/PolyMath | |
| `RT` | | Roassal | `RTShapeBuilder` | https://github.com/ObjectProfile/Roassal2 | |
| `SmaCC` | | SmaCC | `SmaCCParser` | https://github.com/SmaCCRefactoring/SmaCC/tree/master/SmaCC-Runtime.package | |
| `TL` | | Telescope | `TLConnector` | https://github.com/TelescopeSt/Telescope | |
| `TR` | | Trachel (Roassal) | `TRCanvas` | https://github.com/ObjectProfile/Roassal2 | |
| `VO` | | Voyage | `VOMongoRepository` | https://github.com/pharo-nosql/voyage | |
| `WA` |  | Seaside Web Framework | `WAComponent` | https://github.com/SeasideSt/Seaside | |
| `Zn` |  | Zinc Web Components | `ZnClient` | https://github.com/svenvc/zinc | |


## How to contribute
Create a pull request with changes to the current file editing the list of prefixes table


## Ideas
Maybe it is a better way to organize the list prefixes, like having one file per class prefix, with the project name as description.
E.g. the file `WA` (no extension) with content:
```
Seaside Web Framework
https://github.com/SeasideSt/Seaside
```

This will probably simplify the listing and merging of changes, and expose any clash. But the lookup will have to be done via file names.




