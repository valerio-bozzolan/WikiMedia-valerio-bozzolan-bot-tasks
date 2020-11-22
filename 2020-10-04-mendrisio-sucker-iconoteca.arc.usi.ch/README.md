# Importer of multimedia files from https://iconoteca.arc.usi.ch/

## Description

Welcome in the importer of multimedia files for https://iconoteca.arc.usi.ch/.

For more information about the consensus:

https://it.wikipedia.org/wiki/Wikipedia:Raduni/Biblioteca_dell%27Accademia_di_Mendrisio_4_ottobre_2020

## Installation

From this directory:

```
git clone https://github.com/phpquery/phpquery
```

## Usage ##

First download locally one of their collections:

```
wget https://iconoteca..../collection-asd.html
```

Then you can examine that HTML page and bulk-download the available images from it:

```
./parse-html-and-import.php collection-asd.html
```

The you can bulk-upload your files just selecting your directory with the images/metadata and selecting a template:

```
./upload.php images/ template/collezione-biblioteca.php
```

Happy hacking!

## License

Copyright (C) 2020 Valerio Bozzolan

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.