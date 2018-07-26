# CMD Trade

Scripts for transforming trade data for cmd.

# Setup

* `brew install python3`
* Clone this repo, then cd into it.
* `python3 -m venv venv`
* `source venv/bin/activate`
* `pip install -r requirements.txt`
* `jupyter notebook`

At this point your browser should pop open a "jupyer notebook" - this is just an in-browser IDE, with executable code blocks. Once it has, just click on makeV4_trade.

From there, just follow the instuctions in the notebook (which is pretty much "press play"). To preview this you can just click into makeV4_trade.ipynb above.

# Usage

Clone this repo and navigate to this directory then start jupyter with `jupyter notebook` and select the notebook. Follow the in-workbook instructions.

You need two excel spreadsheets as the source data for this transformation.

exports - https://www.ons.gov.uk/redir/eyJhbGciOiJIUzI1NiJ9.eyJpbmRleCI6MywicGFnZVNpemUiOjEwLCJwYWdlIjoxLCJ1cmkiOiIvZWNvbm9teS9uYXRpb25hbGFjY291bnRzL2JhbGFuY2VvZnBheW1lbnRzL2RhdGFzZXRzL3VrdHJhZGVjb3VudHJ5Ynljb21tb2RpdHlleHBvcnRzIiwibGlzdFR5cGUiOiJyZWxhdGVkZGF0YSJ9.396cbpMmoEHc9aHFxIx_PhsEFz-9umTOwkmTHQGxJGI

imports - https://www.ons.gov.uk/redir/eyJhbGciOiJIUzI1NiJ9.eyJpbmRleCI6NCwicGFnZVNpemUiOjEwLCJwYWdlIjoxLCJ1cmkiOiIvZWNvbm9teS9uYXRpb25hbGFjY291bnRzL2JhbGFuY2VvZnBheW1lbnRzL2RhdGFzZXRzL3VrdHJhZGVjb3VudHJ5Ynljb21tb2RpdHlpbXBvcnRzIiwibGlzdFR5cGUiOiJyZWxhdGVkZGF0YSJ9.q9qvUW4qDkYnUFQKNE6B34F3Kp1mxAfOBwDhlOxNLO4
