## Description
Collection of Pharo class prefixes for recognized public libraries/frameworks

## Rationale
Due to the lack of namespaces in [Pharo](https://pharo.org), the community has chosen to prefix class names (or even selectors) with a project-specific prefix to avoid class name clashing. 

## Purpose
The purpose of this list is to provide a public reference of such prefixes that works as a reference catalog, in order to avoid prefix clashing as well.

## List of prefixes

| Class name prefix | Selector prefix | Project name | Sample class name | Project/Repository URI | Other |
| ----------------- | --------------- | ------------ | ----------------- | ---------------------- | ----- |
| `AS` | `#as` | ApplicationSecurity | `ASCheckPoint` | https://github.com/hernanmd/ApplicationSecurity | |
| `Bl` | | Bloc | `BlElement` | https://github.com/pharo-graphics/Bloc | |
| `Bio` | `#bio` | BioSmalltalk | `BioSequence` | https://github.com/hernanmd/BioSmalltalk | |
| `CG` | `#cg` | CodeGenerator | `CGSmalltalk` | https://github.com/hernanmd/CodeGenerator | |
| `CM` | `#cm` | CORMAS | `CMAgent` | https://github.com/cormas/cormas | |
| `FAMIX` | | Famix (Moose) | `FAMIXType` | https://github.com/moosetechnology/Moose | |
| `FT` | | FastTable | `FTTableMorph` | | |
| `Gr` | | Grease Portability Library | `GRPlatform` | 
| `Gf` | | Grafoscopio interactive notebook | `GfWorldMenu` | http://mutabit.com/repos.fossil/grafoscopio/ | |
| `GT` | `#gt` | Glamourous Toolkit | `GTPlayground` | https://github.com/feenkcom/gtoolkit | |
| `Ice` | | Iceberg | `IceRepository` | https://github.com/pharo-vcs/iceberg | |
| `LD` | `#ld` | LanguageDetection | `LDApiClient` | https://github.com/hernanmd/LanguageDetection | |
| `PM` | | PolyMath | `PMMatrix` | https://github.com/PolyMathOrg/PolyMath | |
| `RT` | | Roassal2 | `RTShapeBuilder` | https://github.com/ObjectProfile/Roassal2 | |
| `RS` | | Roassal3 | `RSCircle` | https://github.com/ObjectProfile/Roassal3 | |
| `SmaCC` | | SmaCC | `SmaCCParser` | https://github.com/SmaCCRefactoring/SmaCC/tree/master/SmaCC-Runtime.package | |
| `T` | `#t` | Territorial | `TCountryOrganization` | https://github.com/hernanmd/Territorial | |
| `TL` | | Telescope | `TLConnector` | https://github.com/TelescopeSt/Telescope | |
| `TR` | | Trachel (Roassal) | `TRCanvas` | https://github.com/ObjectProfile/Roassal2 | |
| `PCT` | `#pct` | PhyloclassTalk | `PCTTerritorialRuleTree` | http://phyloclasstalk.github.io/ | |
| `PF` | `#pf` | ProjectFramework | `PFProjectHistory` | https://github.com/hernanmd/ProjectFramework | |
| `VO` | | Voyage | `VOMongoRepository` | https://github.com/pharo-nosql/voyage | |
| `WA` |  | Seaside Web Framework | `WAComponent` | https://github.com/SeasideSt/Seaside | |
| `Zn` |  | Zinc Web Components | `ZnClient` | https://github.com/svenvc/zinc | |
| `Z3950` | `z3050` | Z3950 | `Z3950Query` | https://github.com/hernanmd/Z3950 | |

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




