# Find the bug causing output to be errors instead of expected help returned
this is not as up to date as my post on shopify forums.  I'll get back to this after I complete some more necessary Partner Academy training
I Need to learn how to use shopify_api.py requesting assistance from @federiva @mllemango and more.  I'm new here.  Hello World.

I am thinking I should be able to run "python shopify_api.py help" without auth or session is this correct?
I am thinking these error may have something to do with python installation problem or pip problems or missing dependencies?

Microsoft Windows [Version 10.0.19042.1237]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Givers>cd AppData\Roaming\Python\Python39\Scripts

C:\Users\Givers\AppData\Roaming\Python\Python39\Scripts>python shopify_api.py help
Traceback (most recent call last):
  File "C:\Users\Givers\AppData\Roaming\Python\Python39\Scripts\shopify_api.py", line 102, in <module>
    class Tasks(object):
  File "C:\Users\Givers\AppData\Roaming\Python\Python39\Scripts\shopify_api.py", line 103, in Tasks
    _shop_config_dir = os.path.join(os.environ["HOME"], ".shopify", "shops")
  File "C:\Program Files\Python39\lib\os.py", line 679, in __getitem__
    raise KeyError(key) from None
KeyError: 'HOME'

C:\Users\Givers\AppData\Roaming\Python\Python39\Scripts>
