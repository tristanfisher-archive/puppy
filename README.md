puppy
=====

additional functionality for enabling/disabling puppet

usage:

        puppy [-h] [-v] [--disable disable message | --enable]
                     [--timeout [integer]]

        puppet command line wrapper with extended functionality

        optional arguments:
          -h, --help            show this help message and exit
          -v, --version         show script version and exit
          --disable disable message
                                disables the host's puppet agent and updates
                                /etc/motd. must be followed by a string or quoted
                                group of strings
          --enable              enables the host's puppet agent
          --timeout [integer]   specify the number of days before resuming puppet.
                                [defaults to 1]
