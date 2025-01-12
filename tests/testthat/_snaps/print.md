# webfakes_app_process

    Code
      proc
    Output
      <webfakes_app_process>
      state:
        not running
      auto_start:
        TRUE
      process id:
        none
      http url:
        NA
      fields and methods:
        get_app()              # get the app object
        get_port()             # query (first) port of the app
        get_ports()            # query all ports of the app
        get_state()            # query web server process state
        local_env(envvars)     # set temporary environment variables
        start()                # start the app
        url(path, query)       # query url for an api path
        stop()                 # stop web server process
      # see ?webfakes_app_process for details

