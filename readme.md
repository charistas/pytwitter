# pytwitter

---

**pytwitter** allows you to delete all your tweets. Even if they're more than 3,200. It uses the excellent [Tweepy][tw] Twitter Python library.

---

### Installation

1. Clone this repo and `cd` in.
2. `$ virtualenv env`
3. `$ cd env`
4. `$ pip install tweepy`

### Usage

1. [Generate][access] an access token to access your own account.
2. Enter the corresponding tokens in `config.py`
3. `$ python pytwitter.py [-h] [-r | -a timeframe timeframe]`  
(assuming you're still inside the `env`)

[tw]: https://github.com/tweepy/tweepy
[access]: https://apps.twitter.com/app/new