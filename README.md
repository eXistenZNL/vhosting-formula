# Enrise Vhosting Formula

[![Documentation](https://readthedocs.org/projects/vhosting-formula/badge/?version=master)](http://vhosting-formula.readthedocs.org/)

This Saltstack formula takes care of provisioning your webstack, creates vhosts and databases and serves as an extendable base.

This wraps around several other other [Enrise formulas](https://github.com/enrise/?query=formula).

The `pillar.example` provides an complete overview of the possibilities
but there is more…

> **note**
>
> This formula has **only been tested on Ubuntu 14.04**.
>
> :   It will most likely not work on other platforms due to hardcoded
>     package names and Ubuntu-specific commands.
>
