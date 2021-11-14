---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [Path](./node-core-library.path.md)

## Path class

Common operations for manipulating file and directory paths.

<b>Signature:</b>

```typescript
export declare class Path 
```

## Remarks

This API is intended to eventually be a complete replacement for the NodeJS "path" API.

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [convertToBackslashes(inputPath)](./node-core-library.path.converttobackslashes.md) | <code>static</code> | Replaces POSIX-style slashes with Windows-style backslashes |
|  [convertToSlashes(inputPath)](./node-core-library.path.converttoslashes.md) | <code>static</code> | Replaces Windows-style backslashes with POSIX-style slashes. |
|  [formatConcisely(options)](./node-core-library.path.formatconcisely.md) | <code>static</code> | Formats a path to look nice for reporting purposes. |
|  [isDownwardRelative(inputPath)](./node-core-library.path.isdownwardrelative.md) | <code>static</code> | Returns true if the specified path is a relative path and does not use <code>..</code> to walk upwards. |
|  [isEqual(path1, path2)](./node-core-library.path.isequal.md) | <code>static</code> | Returns true if <code>path1</code> and <code>path2</code> refer to the same underlying path. |
|  [isUnder(childPath, parentFolderPath)](./node-core-library.path.isunder.md) | <code>static</code> | Returns true if "childPath" is located inside the "parentFolderPath" folder or one of its child folders. Note that "parentFolderPath" is not considered to be under itself. The "childPath" can refer to any type of file system object. |
|  [isUnderOrEqual(childPath, parentFolderPath)](./node-core-library.path.isunderorequal.md) | <code>static</code> | Returns true if "childPath" is equal to "parentFolderPath", or if it is inside that folder or one of its children. The "childPath" can refer to any type of file system object. |
