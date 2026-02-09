# Problems

## setuid file

Permissions for `/usr/lib/erlang/p1_pam/bin/epam` are set by this task.  I am unsure whether that change will persist through updates of the `erlang-p1-pam` package, which owns the file.  Verify.

## outdated options

Check the log file at startup.  It says a lot of the modules I am using are outdated, and it is substituting newer modules for some.  Get a better understanding of what modules would be best and specify them in the configuration.
