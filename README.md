# Plans

## user management

I think ejabberd can user kerberos.  That's probably a good idea.  In the unlikely event that a bunch of people start using this server, if we decide to move to a different protocol, it would be nice to not make everyone register again.  It could also be nice to offer other services, like email, using the same credentials.


# Problems

## outdated options

Check the log file at startup.  It says a lot of the modules I am using are outdated, and it is substituting newer modules for some.  Get a better understanding of what modules would be best and specify them in the configuration.

## setuid file

Permissions for `/usr/lib/erlang/p1_pam/bin/epam` are set by this task.  I am unsure whether that change will persist through updates of the `erlang-p1-pam` package, which owns the file.  Verify.
