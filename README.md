# A simple test for hadoop
Compute max temperature for each year from NCDC data.

The code comes from book "Hadoop - The Definitive Guide, 4th"

# Build
`mvn clean package`

# Run
`rm -rf out/`

`hadoop jar target/my-hadoop-app-1.0-SNAPSHOT.jar com.mycompany.app.MaxTemperature input/ncdc/sample.txt  out`
