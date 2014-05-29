jsonfmt - JSON FORMAT
=====================

#### Installation

```shell
npm install jsonftm -g
```

#### Example 1 - output

**~/Desktop/file.json** contents

```json
[{"foo":"bar"},{"foo":"bar"},{"foo":"bar"},{"foo":"bar"}]
```

**Run command**

```shell
jsonfmt -f ~/Desktop/file.json
```

**Example output**

```json
[
    {
        "foo": "bar"
    },
    {
        "foo": "bar"
    },
    {
        "foo": "bar"
    },
    {
        "foo": "bar"
    }
]
```

-------------------------------------------------------------

##### Example 2 - output to file

```shell
jsonfmt -f ~/Desktop/file.json > ~/Desktop/fmt_file.json
```