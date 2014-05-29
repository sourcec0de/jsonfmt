jsonfmt - JSON FORMAT
=====================

run `npm install jsonftm -g` to install

#### Examples

**~/Desktop/file.json** contents
```json
[{"foo":"bar"},{"foo":"bar"},{"foo":"bar"},{"foo":"bar"}]
```

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