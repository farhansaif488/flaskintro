# flaskintro

Flask is a lightweight microframework. I've been a big fan of flask microframework since 2020. 
This repo is for [farhansaif.xyz](https://farhansaif.xyz) 

The deployed branch contains remote files. Master and deployed repos are same. Other branches contain experimental codes or new features that might be added to the site. 

# To do
1. Add project descriptions.
2. Audio stream api.
3. Online pdf reader for users.
4. Online compiler ? sounds interesting. 

Might add more. Idk.
# Run
You can use it anywhere however you want for edu/biz purpose i don't really care. In case you are not farhan saif just make sure you deleted my name or something? 
```
$ git clone git:github.com:overlorde/flaskintro.git
$ cd flaskintro
$ source env/bin/activate
$ python3 -m pip install -r requirements.txt
$ gunicorn --bind 0.0.0.0:5000 wsgi:app
```
# Running it on background
A wsgi file with gunicorn and systemd unit it works just fine on my low cost debian vps. (Ik vps is a bit overkill, use heroku or something) If you can use a vps cause its more fun?
