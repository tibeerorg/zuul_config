# Zuu config repository

In this repository you'll find the core configuration for the zuul server.

**zuul.d** contains the general pipeline, job and project configuration.

**playbooks** contains a collection of basic tasks which run with the *base* job.

If you want to have the logging server working, you need to set the value
in *zuul_config/playbooks/base/post-logs.yaml* the correct IP / DNS name.

