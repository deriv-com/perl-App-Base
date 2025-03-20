# NAME

App::Base - modules implementing common methods for applications

# VERSION

This document describes App::Base version 0.05

# SYNOPSIS

    use App::Base;

# DESCRIPTION

This distribution provides modules that implement common methods for writing scripts and daemons.

- [App::Base::Script](https://metacpan.org/pod/App%3A%3ABase%3A%3AScript)

    Role implementing basic functionality for scripts

- [App::Base::Script::OnlyOne](https://metacpan.org/pod/App%3A%3ABase%3A%3AScript%3A%3AOnlyOne)

    Role to allow only one running instance of the script

- [App::Base::Daemon](https://metacpan.org/pod/App%3A%3ABase%3A%3ADaemon)

    Role implementing basic functionality for daemons

- [App::Base::Daemon::Supervisor](https://metacpan.org/pod/App%3A%3ABase%3A%3ADaemon%3A%3ASupervisor)

    Role implementing methods to support supervision and zero downtime reloading for daemons.

# CONTRIBUTORS

The following people contributed to this module:

- Calum Halcrow
- Chris Travers
- Fayland Lam
- Jean-Yves Sireau
- Kaveh Mousavi Zamani
- Matt Miller
- Nick Marden
- Pavel Shaydo
- Tee Shuwn Yuan


Minor update to documentation.