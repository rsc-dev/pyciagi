# pyciagi
Non-official API for real-time trains position across Poland.

Usage
-----
```
import pyciagi

difficulties = pyciagi.difficulties_by_voivodeship(pyciagi.POMORSKIE)
trains = pyciagi.trains_by_voivodeship(pyciagi.SLASKIE)
```