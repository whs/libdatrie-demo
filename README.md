# libdatrie meson demo
This project demo how meson projects could use libdatrie as dependency, without requiring the library user to install libdatrie beforehand.

## Usage

```sh
meson setup builddir
cd builddir
ninja test
```

## License
This project contains code from libdatrie in utils.c, utils.h, test_walk.c

```
Copyright (C) 2006-2021 libdatrie contributors

This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
```

Rest of the files, including build scripts are licensed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/legalcode).
