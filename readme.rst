
Overview
************

foo bar

.. code:: shell

    shell> generator.py -h
    Usage: generator.py [options] job,...

    Arguments:
      job,...               a list of jobs (like 'source' or 'copy-files',
                            without the quotes) to run
      x                     use 'x' (or some undefined job name) to get a 
                            list of all available jobs from the configuration file

    Options:
      -h, --help            show this help message and exit
      -c CFGFILE, --config=CFGFILE
                            path to configuration file containing job definitions
                            (default: config.json)
      -q, --quiet           quiet output mode (extra quiet)
      -v, --verbose         verbose output mode of job processing
      -w, --config-verbose  verbose output mode of configuration processing
      -l FILENAME, --logfile=FILENAME
                            log file
      -s, --stacktrace      enable stack traces on fatal exceptions
      -m KEY:VAL, --macro=KEY:VAL
                            define/overwrite a global 'let' macro KEY with value
                            VAL
      -d, --daemon          (EXPERIMENTAL - DON'T USE) puts the generator in
                            daemon mode
      -I, --no-progress-indicator
                            suppress animated progress indication

