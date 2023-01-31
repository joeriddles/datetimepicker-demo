# DateTimePicker + Luxon with ISO datetimes

This repo demonstrates how to use the jQuery [DateTimePicker](https://xdsoft.net/jqplugins/datetimepicker/) plugin and [Luxon](https://moment.github.io/luxon/#/) to get ISO timestamps from the DateTimePicker element while using a custom format for the dates.

![](resources/screenshot.png)

---

Init `datetimepicker` submodule after cloning
```shell
git submodule init 
git submodule update
```

To run
```shell
python -m http.server 80
```

_Note_: `Luxon` is added directly to the repo (`luxon.js`), but `DateTimePicker` is added as a git submodule and requires initialization after cloning the git repo.
