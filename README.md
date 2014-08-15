# FLUD

Visual Twitter streams for queries.

## Setup

* Setup `config.py`
    * Setup your Twitter info (Visit
        [https://apps.twitter.com/](https://apps.twitter.com/) to set it
        up if you need to.)
    * Set a login username and password
* Setup a virtualenv
    * `virtualenv ~/env/flud --no-site-packages`
    * Activate it: `source ~/env/flud/bin/activate`
* Install dependencies: `pip install -r requirements.txt`
* Run the server: `python application.py`

If you're deploying it to a server, you can use the setup script in
`setup/setup.sh`.