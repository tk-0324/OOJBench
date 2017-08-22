# OOJBench

- Benchmark data generator for order-oriented join, an implementation of hinting join.


## Component
- dataGen.py: data generator
- conf.json: configuration file for the generator
```
{
"N": {
        "value": 1000,
        "description": "The number of tuples in the joined result."
},
"k": {
        "value": 10,
        "description": "The number of attributes on R."
},
"l": {
        "value": 10,
        "description": "The number of attributes on S "
},
"s": {
        "value": 1,
        "description": "The number of attributes for order-oriented join on R."
},
"t": {
        "value": 1,
        "description": "The number of attributes for order-oriented join on S."
},
"z": {
        "value": 10,
        "description": "The number tuples per join key value."
}
}
```