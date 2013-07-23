Has your legal department been asking you lately to give them a list of licenses for all of your python software? Do you [over-]use virtualenv and let your developers install whatever crap they want to in production? If so, then this might be the tool for you. It looks in pypi and tries to get a guess as to what licenses your installed projects use, and then it spits that out in CSV form.

Usage:

    /path/to/virtualenv/bin/pip freeze | licenses_from_pypi


This software requires `python-tornado >= 3.0` to be installed.
