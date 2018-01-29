# Utilities and random js files


## files.js

file-functions for node.js that return Promises

```
    import {
        textFileContentPromiseFromPath,
        writeTextInFilePromiseFromPathAndString,
        concatenateFiles,
        copyFile,
        deleteFile
    } from "./files.js"
```


## operators.js

Common operands as functions


## utility.js

```
    import {
        createDebouncedFunction,
        createThrottledFunction,
        createCustomRound,
        fillArrayWithFunctionResult,
        chainPromises,
        doNTimes,
        chainPromiseNTimes,
        timeCallback,
        timePromise,
        memoizeAsStrings
    } from "path.../utility.js";
```


## blobs.js

```
    import {
        downloadBlob
    } from "path.../blobs.js";
```

## About

### License

[CC0](license.txt)

### Related

 * [fnk](https://github.com/seanohue/fnk)
 * jQuery
 * lodash
 * ramda