# Faces
Java code sample for using the Project Oxford Faces API

You will need to get an API key for the Project Oxford Faces API. At the time of writing, it is a free API.

Using your IDE, you will need to update the build path to add the libraries in the `libs` folder as external jars, or something.

Sample URL: "http://www.businessstudynotes.com/wp-content/uploads/2015/09/Role-of-Group.jpg"

JSON Result: 
```
[
    {
        "faceRectangle": {
            "top": 107,
            "left": 343,
            "width": 81,
            "height": 81
        },
        "faceAttributes": {
            "gender": "female",
            "age": 37.3
        }
    },
    {
        "faceRectangle": {
            "top": 42,
            "left": 242,
            "width": 69,
            "height": 69
        },
        "faceAttributes": {
            "gender": "male",
            "age": 51.7
        }
    },
    {
        "faceRectangle": {
            "top": 76,
            "left": 155,
            "width": 62,
            "height": 62
        },
        "faceAttributes": {
            "gender": "female",
            "age": 35
        }
    },
    {
        "faceRectangle": {
            "top": 60,
            "left": 80,
            "width": 56,
            "height": 56
        },
        "faceAttributes": {
            "gender": "male",
            "age": 27.4
        }
    }
]
```

Sample URL: http://www.stopfryingyourbrain.com/wp-content/uploads/2014/12/A_party.gif

JSON Result: 
```
[
    {
        "faceRectangle": {
            "top": 49,
            "left": 418,
            "width": 199,
            "height": 199
        },
        "faceAttributes": {
            "gender": "male",
            "age": 29.9
        }
    },
    {
        "faceRectangle": {
            "top": 140,
            "left": 532,
            "width": 195,
            "height": 195
        },
        "faceAttributes": {
            "gender": "female",
            "age": 25.1
        }
    },
    {
        "faceRectangle": {
            "top": 83,
            "left": 19,
            "width": 188,
            "height": 188
        },
        "faceAttributes": {
            "gender": "male",
            "age": 28.1
        }
    },
    {
        "faceRectangle": {
            "top": 279,
            "left": 34,
            "width": 186,
            "height": 186
        },
        "faceAttributes": {
            "gender": "female",
            "age": 26.6
        }
    },
    {
        "faceRectangle": {
            "top": 180,
            "left": 273,
            "width": 173,
            "height": 173
        },
        "faceAttributes": {
            "gender": "female",
            "age": 25.2
        }
    }
]
```
