DID YOU MEAN: COMPLETE ACTIVITY (teacher copy, contains the solution)

What is in this folder
- did_you_mean.py      : the full working solution.
- did_you_mean_app.py  : the Gradio web page (step 9). It uses did_you_mean.py.
- requirements.txt     : gradio and a recent jinja2 (needed only for the web page).

Setup
1. Python 3.10 or newer.
2. For the web page:  pip install -r requirements.txt

Run
- The program:   python did_you_mean.py        (Windows: py did_you_mean.py)
- The web page:  python did_you_mean_app.py    then open http://127.0.0.1:7860

Expected results (teacher): the SCORE line is 8/12, 9/12, 11/12 for versions A, B and C. "lasi" still fails in all three.
Do not share this folder with students: the boilerplate zip is the student copy.
