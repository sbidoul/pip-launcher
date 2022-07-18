# pip-launcher

Download and run `pip` in the current python environment without installing it. 

This script downloads the latest supported pip version in a `__pip_launcher_cache__`
directory next to it. It then runs pip in the python environment that was used to lauch
it, alleviating the need to install pip in the target python environment.

To force dowloading the latest supported pip version, run the script with a single
`upgrade-pip` argument.

This script works with python 2.7 and 3.5+.

Created by Stéphane Bidoul, based on an idea by Paul Moore
(https://github.com/pypa/pip/issues/11243)
