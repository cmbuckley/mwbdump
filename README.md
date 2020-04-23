# mwbdump

A script for dumping [MySQL Workbench](https://www.mysql.com/products/workbench/) files to SQL, very similar to the format for mysqldump.

## Usage

```bash
mwbdump [OPTION]... workbench-file
```

### Options

#### -n / --no-create-db
Suppress the CREATE DATABASE IF NOT EXISTS ... statements.

#### -t / --no-create-info
Suppress the CREATE TABLE IF NOT EXISTS ... statements.

#### -d / --no-data
Don't write row INSERT statements.

#### --skip-add-drop-table
Suppress the DROP TABLE IF EXISTS ... statements.

#### -V / --version
Output version information and exit.

#### -h / --help
Display help message and exit.
