relaxml -- gut edition
======================

A [`gut`
implementation](http://maxogden.com/#blog/gut-hosted-open-data-filets)
of the [`relaxml` Python library](https://github.com/zachwill/relaxml).


Usage
-----

    curl -X POST http://relaxml.herokuapp.com -H "X-callback: http://my.site.com" --data-binary @file.xml


Locally
-------

You can start up the server from the command line:

    python app.py

And to test it out:

    curl -X POST http://localhost:5000 -H "X-callback: http://www.postbin.org/yc0zqh" --data-binary @note.xml
