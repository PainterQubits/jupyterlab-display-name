# JupyterLab Display Name

JupyterLab server extension that adds a display name field to the login page.

## Installation

Coming soon.

## Development

To develop, the following dependencies must be installed:

- [Python](https://www.python.org/downloads/)
- [Hatch](https://hatch.pypa.io/latest/install/)

To run JupyterLab with this extension in development mode, run:

```
hatch run jupyterlab:start
```

If the contents of jupyter_server_config.json changes, the old environment must be removed
by running:

```
hatch env remove jupyterlab
```
