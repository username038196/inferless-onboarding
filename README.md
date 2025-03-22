##Setting up code to deploy (Github)

Ensure app.py is placed in the root directory for Inferless to work with “Github”.

```
pip install inferless
```

###Step 1: 
Import the Inferless library and use the @request and@response annotations for input and output schemas using Pydantic.

###Step 2 
Create a class InferlessPythonModel with initialize and infer methods to load the model and handle inference.

- initialize - Should help take care for setting up the model and pulling the models weitgh
- infer - Should take the input and return the pydantic object of type response 

Example files are in the repo 
