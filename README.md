# Freeway Dataset

There are 2 freeway datasets for MongoDB. It will create the database `freeway` & collections: `highwaydata` & `highwaystations`.

## Usage
```
$ mongorestore -d freeway -c highwaydata highwaydata.bson
$ mongorestore -d freeway -c highwaystations highwaystations.bson
```

## License
This program is licensed under the "MIT License". Please see the file [LICENSE](https://github.com/ronniesong0809/freeway-dataset/blob/master/LICENSE) in the source distribution of this software for license terms.