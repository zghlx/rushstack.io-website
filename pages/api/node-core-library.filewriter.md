---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/node-core-library](./node-core-library.md) &gt; [FileWriter](./node-core-library.filewriter.md)

## FileWriter class

API for interacting with file handles.

<b>Signature:</b>

```typescript
export declare class FileWriter 
```

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [close()](./node-core-library.filewriter.close.md) |  | Closes the file handle permanently. No operations can be made on this file handle after calling this. Behind the scenes it uses <code>fs.closeSync()</code> and releases the file descriptor to be re-used. |
|  [open(path, flags)](./node-core-library.filewriter.open.md) | <code>static</code> | Opens a new file handle to the file at the specified path and given mode. Behind the scenes it uses <code>fs.openSync()</code>. The behaviour of this function is platform specific. See: https://nodejs.org/docs/latest-v8.x/api/fs.html\#fs\_fs\_open\_path\_flags\_mode\_callback |
|  [write(text)](./node-core-library.filewriter.write.md) |  | Writes some text to the given file handle. Throws if the file handle has been closed. Behind the scenes it uses <code>fs.writeSync()</code>. |
