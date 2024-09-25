## MULTIPLE CHOICE QUESTION GENERATOR

This is a repo to test out using the [ell](https://docs.ell.so/) package.

The notebook mc_question_generator.ipynb is a demostration of creating a multiple choice question generator using the ell package and gpt-4o (I would love to try o1-preview but I'm not level 4 on API!).

If this is the first time using this repo it is suggested to create a local environment from the requirements.txt file with python 3.11. 

```
python3.11 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

Place any LLM provider API keys in a .env file.

To run the studio and see the stored functions and results:
```
ell-studio --storage ./logdir
```
The studio can then be viewed on http://localhost:5555.
