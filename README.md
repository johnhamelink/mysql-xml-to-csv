# mysql-xml-to-csv.c


This tool, [taken from a stackoverflow answer](https://stackoverflow.com/a/67007702/315827), allows for easily conversion of MySQL output into a CSV, making use of the MySQL client's XML output feature.

## Installation

Make sure you have the `expat` library installed, then simply run `make`, and then copy the binary it produces into your `PATH`.

## Example Usage

```sh
mysql --xml < query.sql | mysql-xml-to-csv > out.csv
```
