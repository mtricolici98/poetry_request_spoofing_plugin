# Poetry Request Spoofing Plugin

When using poetry form some private repositories, the host of the repository may block
the `python-requests` `user-agent`.

This repository aims to fix that by facilitating a way to replace that with any desired user agent.