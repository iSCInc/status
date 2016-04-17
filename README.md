# [Stashboard Software for iSC Inc. Status](https://iscinc-status.appspot.com)

[![Build Status](https://secure.travis-ci.org/iSCInc/status.png?branch=master)](https://travis-ci.org/iSCInc/status)

**Stashboard** was written by Twilio, Inc. and is used by iSC Inc. to provide status informations about iSC Inc. wikis.

## Installation

1. Download and install the [App Engine SDK for Python][appengine]
2. `git clone git://github.com/twilio/stashboard.git` or `git clone git://github.com/iSCInc/status.git`
3. Add your application id to `app.yaml`
4. Open the SDK, choose `File > Add Existing Application...` and select the `stashboard` folder inside the cloned repository
5. Update the settings in `settings.py`
6. Visit http://your-app-id.appspot.com/admin/setup to complete the installation

From here you can either run Stashboard locally in the [App Engine development environment][local] or [deploy to Appspot][deploy].
See the [Getting Started](http://code.google.com/appengine/docs/python/gettingstarted) guide for a basic overview of the App Engine platform.

[local]: http://code.google.com/appengine/docs/python/gettingstarted/devenvironment.html
[deploy]: http://code.google.com/appengine/docs/python/gettingstarted/uploading.html
[appengine]: http://code.google.com/appengine/downloads.html#Google_App_Engine_SDK_for_Python

## Supported domains

We use the Freenom TLD service **`.tk`**, CloudFlare Proxy and DNS and the Google App Engine Domains:
 - http://iscinc-status.tk
 - http://iscinc-status.tk
 - http://*.iscinc-status.tk (type something like this: http://something-i-type.iscinc-status.tk)
 - https://app.iscinc-status.tk
 - http://app.iscinc-status.tk
 - http://status.iscinc-status.tk
 - https://iscinc-status.appspot.com/
 - http://iscinc-status.appspot.com/

## Documentation

Full documentation can be found on [Read The Docs](http://readthedocs.org/docs/stashboard/en/latest)!

## Community

All Stashboard development and discussion happens in the [Stashboard google group](https://groups.google.com/forum/#!forum/stashboard)!

To keep up to date, you can follow [@stashboard](http://twitter.com/stashboard) on Twitter or join the [#stashboard](irc://irc.freenode.net/stashboard) channel on freenode.

## Development

You'll need to install a couple more packages to hack on Stashboard
  
    pip install -r requirements.txt

To run the unit tests, 

    python tests/runner.py tests

## Acknowledgements
* Buttons by [Necolas](https://github.com/necolas/css3-github-buttons)
* Fugue icons by [Yusuke Kamiyamane](http://p.yusukekamiyamane.com/)
* Iconic icons by [P.J. Onori](http://somerandomdude.com/projects/iconic/)
* OAuth support via [simplegeo/python-oauth2](https://github.com/simplegeo/python-oauth2)
