
# Command Line

To list available commands execute `nfd help`:

    $ nfd help

## nfd host

    Usage: nfd use <host> [<port>]

    The nfd host is the server running the nfd system.

    Example:
    $ nfd use localhost 3223

## login

    Usage: nfd login

    There are two ways to authenticate to the nfd host, either with your username/password login or with your github account.

### login with username/password

    $ nfd login
    prompt: nfd username / password login (y/n): y
    prompt: username: <username>
    prompt: password: <password>

### login with github account

First generate a new github personal access token in [https://github.com/settings/applications](https://github.com/settings/applications), remembering to select the 'repo' and 'user' scopes.

    $ nfd login
    prompt: nfd username / password login (y/n): n
    prompt: github access token: <personal access token>

## logout

    Usage: nfd logout

    Logout from the nfd host.

    Example:
    $ nfd logout

