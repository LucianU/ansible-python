python
======
Installs system and python-specific packages. Creates a location for virtual envs.

Role Variables
==============
| Variable | Description | Default value |
|----------|-------------|---------------|
|`python_packages`| List of system and python packages | `See below` |
|`python_virtualenvs_dir`| Path to virtual envs dir | `/var/local/virtualenvs` |

Default value for `python_packages`:
- build-essential
- git
- liblcms1-dev
- libfreetype6-dev
- libjpeg8-dev
- zlib1g-dev
- python-dev
- python-pip
- python-psycopg2

Dependencies
============
none

License
=======
BSD
