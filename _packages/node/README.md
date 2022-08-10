# Apple Hardware Data

Brought to you by the [Hack Different](https://hackdifferent.com) team.

## Introduction

This is a package with data files sourced from
the [hack-different/apple-knowledge](https://github.com/hack-different/apple-knowledge/tree/main/_data)
repository.  Updates to that repository will automatically update this package, therefore no attempt should
be made to update the data files by any other method.

## Accessing the Data

For the time being, there is only one simple API:

```js
import { getData } from 'apple-data';

// 'cores' is the path of the data file without extension in the _data directory of
// apple-knowledge

const cores_data = await getData('cores');
```

## Credits

* [Hack Different - Community](https://hackdifferent.com)
* [Hack Different - Discord](https://hackdifferent.com/discord)

Package and repo created and maintained as a labor of love by [`rickmark`](https://github.com/rickmark)