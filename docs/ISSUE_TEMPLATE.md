## Reporting bugs/issues

* When reporting a bug/issue:
    * Ensure that you are using the latest release.
    * Revert any custom modifications or environment varibles to insure they're not the cause.

* Please provide the following information:
    * OS/distribution version (command for your OS may differ):
    IE:
    ```bash
    user@host:~$ lsb_release -a
    No LSB modules are available.
    Distributor ID: Ubuntu
    Description:    Ubuntu 16.04.3 LTS
    Release:        16.04
    Codename:       xenial
    ```

    * Docker version:
    IE:
    ```bash
    user@host:~$ docker --version
    Docker version 17.05.0-ce, build 89658be
    ```

    * Labels from container:
    IE:
    ```bash
    user@host:~$ docker inspect goofball222/freeradius:latest
    ...
                "Labels": {
                    "org.label-schema.build-date": "2018-08-19T20:08:26Z",
                    "org.label-schema.license": "Apache-2.0",
                    "org.label-schema.name": "FreeRadius Docker Container",
                    "org.label-schema.schema-version": "1.0",
                    "org.label-schema.url": "https://github.com/goofball222/freeradius",
                    "org.label-schema.vcs-ref": "003adec",
                    "org.label-schema.vcs-url": "https://github.com/goofball222/freeradius.git",
                    "org.label-schema.vendor": "goofball222",
                    "org.label-schema.version": "3.0.17"
                }
    ...
    ```

    * Details on how to reproduce the trouble, if available:
