sa-influxdb
===========
[![Build Status](https://travis-ci.org/softasap/sa-influxdb.svg?branch=master)](https://travis-ci.org/softasap/sa-influxdb)


Example of use: check box-example

Simple:

```YAML

```

```YAML


     - {
         role: "sa-influxdb"
       }

```


Advanced:

```YAML


     - {
         role: "sa-influxdb",
         influxdb_version: "1.2.2"
       }


```

Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-influxdb role using the command

`
   ansible-galaxy install softasap.sa-influxdb
`

the role will be available in the folder library/softasap.sa-influxdb
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-influxdb"
       }

```



Copyright and license
---------------------


Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

