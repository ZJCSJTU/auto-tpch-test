# TPC-H  tests for pyverdict
- Run on ```salat2.eecs.umich.edu```
- Run ```./gendata [size]``` to generate TPC-H data of [size] GB. This will put the file on Hadoop, and create a database and tables on hive.
- Run ```./tpchtest``` to see how to test pyverdict on TPC-H data.
- Currently only supports Presto connection
- I am still working on it.
- Will handle data generation and test for different size data
