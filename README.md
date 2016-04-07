# json2csv
A python utility to convert a bunch of nested json files to a csv file

## Usage

```bash
python json2csv.py <folder_name> [output_file]
```

**json2csv** processes all the `*.json` files in the specified folder.
If no output file is mentioned, the output is printed on *stdout*.

## Sample files

The folder `sample/` contains two files `sample1.json` and `sample2.json`.
To run **json2csv** on the `sample/` and write the output to `sample.csv`, run the following:

```bash
python json2csv.py sample sample.csv
```
