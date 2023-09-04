# WinHaste #

**WinHaste** is a Windows commandline client for [hastebin.com](https://hastebin.com).

## Download ##

Binary releases are available [here](https://github.com/ajryan/WinHaste/releases).

## Usage ##

    WinHaste.exe [service url] [file to haste]

Both parameters are optional.

The `[service url]` parameter defaults to `https://pbbin.com`

When the `[file to haste]` parameter is omitted, WinHaste reads from the console standard input stream.

Running WinHaste.exe with no parameters will allow you to type a snippet followed by `Ctrl+Z` to send.
You can also pipe a file to WinHaste.exe to post, for example `type test.txt | WinHaste.exe`.

The pbbin URL of your snippet is copied to the clipboard upon success.

## HasteBin ##

[hastebin.com](https://hastebin.com) was created by John Crepezzi. See the [about.md](https://hastebin.com/about.md) and [GitHub repo](https://github.com/seejohnrun/haste-server) for more.
