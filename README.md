# gpkgtogeojson
Conversion of gpkg format file to a formatted file geoJson

usage: python main.py [-d DIRECTORY] [-o OUTPUT] input.gpkg

Convert a GeoPackage (GPKG) file to a GeoJSON file.

positional arguments:
  input_file           Input GPKG file (if not provided, will read from stdin)

options:
  -h, --help           show this help message and exit
  -d, --dir DIR        Directory of the input GPKG file (default: current directory)
  -o, --output OUTPUT  Output GeoJSON file name (default: output.geojson)
