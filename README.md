# TPC-DI

## Repo content
- *Spark.ipynb*, containing TPC-DI implementation for Spark SQL.
- *ddl*, containing TPC-DI's queries.

## Download .zip from tpc.org.
1. Download .zip folder from offical souce and unzip them.
2. Change the folder PDGF to lowercase: pdgf
3. Inside pdgf folder is PDGF.jar change to lowercase too.


## Generate the data

The next instructions works under java-8-openjdk. We tried under java-11-openjdk and it didnt work. To change versions in java, you can try in linux:

``
sudo update-alternatives --config java
``

If it does not work, you should change environment variable with the java-8-openjdk path in JAVA_HOME.

To see DIGen arguments, you can run the next command to see how configure the scale factor (sf) and directory (o).

``
java -jar DIGen.jar -h
``


## Author

### Contributors

- **[Cools Arnaud](https://github.com/Arcools-ulb)**
- **[Dubois Alexandre](https://github.com/aedubois)**
- **[Rocca Valerio](https://github.com/ValerioRocca)**
- **[Salazar Maria Camila](https://github.com/mariacsalazar)**
