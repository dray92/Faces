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
