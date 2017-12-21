# hyperdrive-archiver

The API is the same as [hypercore-archiver](https://github.com/mafintosh/hypercore-archiver), with support for hyperdrives.

[![NPM](https://nodei.co/npm/hyperdrive-archiver.png)](https://nodei.co/npm/hyperdrive-archiver/)

## `archiver.health(archive)`

Return the health of the archive. The `archive` parameter should be the return value from `archiver.get` function.

## `archiver.remove()`

## `archiver.add()`

## `archiver.list()`

## `archiver.get(link, [opts], cb)`

Resolve the given link and get the archive back that matches the given link.

## `archiver.metadata(archive, [opts], cb)

Get the metadata such as the file list and the dat.json file from the archive.

## `archiver.close()`

Closes the archive
