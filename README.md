# ThingsDB syntax highlighting for vscode

This extension provides syntax highlighting for the ThingsDB language.

## Features

- Adds syntax highlighting for the `.ti` file extension.

## Requirements

This extension has no dependencies.

## Known Issues

None

## Release Notes

### 0.1.12

Update syntax highlighting with `vmap` function.

### 0.1.11

Update syntax highlighting with `search` function.

### 0.1.10

Update syntax highlighting with `to_thing` function.

### 0.1.9

Update syntax highlighting with `closure` function.

### 0.1.8

Update repository name.

### 0.1.7

Update syntax highlighting with `set_default_deep` function and `return`, `if..else` and `for..in` statements, including `break` and `continue`.

### 0.1.6

Update syntax highlighting with `is_time_zone` function.

### 0.1.5

Update syntax highlighting with `restrict` and `restriction` functions.

### 0.1.4

Update syntax highlighting with task functions and removed timer functions:
* Added `task` function.
* Added `tasks` function.
* Added `is_task` function.
* Added `at` function.
* Added `again_in` function.
* Added `again_at` function.
* Added `cancel` function.
* Added `closure` function.
* Added `set_closure` function.
* Added `args` function.
* Added `set_args` function.
* Added `owner` function.
* Added `set_owner` function.
* Added `err` function. *(as chained function)*
* Removed `del_timer` function.
* Removed `has_timer` function.
* Removed `new_timer` function.
* Removed `set_timer_args` function.
* Removed `timer_args` function.
* Removed `timer_info` function.
* Removed `timers_inf` function.

### 0.1.3

Update syntax highlighting with `json_dump` and `json_load` functions.

### 0.1.2

Update syntax highlighting with `log` and `refresh_module` functions.

### 0.1.1

Update syntax highlighting with `clear` function.

### 0.1.0

Update syntax highlighting (version 1.x of ThingsDB):
* Added `room` and `is_room` function.
* Removed `def`, `watch` and `unwatch` function.
* Renamed function `event_id` to `change_id`.
* Removed deprecated `READ`, `WATCH`, `EVENT` and `MODIFY` keywords.
* Added `JOIN` and `CHANGE` keywords.

### 0.0.37

Update syntax highlighting with `to_type` function.

### 0.0.36

Update syntax highlighting with `deploy_module` function.

### 0.0.35

Update syntax highlighting with `extend_unique` function.

### 0.0.34

Update syntax highlighting with `is_unique` and `unique` functions.

### 0.0.33

Update syntax highlighting with `is_mpdata` and `load` functions.

### 0.0.32

Update syntax highlighting with `copy` and `dup` functions.

### 0.0.31

Update syntax highlighting with `del_timer`, `has_timer`, `new_timer`, `set_timer_args`, `timer_args`, `timer_info` and `timers_info` functions.

### 0.0.30

Update syntax highlighting with `first`, `last`, `is_regex` and `regex` functions.

### 0.0.29

Update syntax highlighting with `equals` function.

### 0.0.28

Update syntax highlighting with `then`, `else`, `cancelled_err`, `future`, `is_future`, `has_module`, `del_module`, `module_info`, `modules_info`, `new_module`, `rename_module`, `set_module_conf`, `set_module_scope` and `restart_module` functions.
Update syntax highlighting with `QUERY` and `EVENT` as privilege constants.

### 0.0.27

Update syntax highlighting with `is_datetime`, `is_timeval`, `datetime`, `timeval`, `set_time_zone`, `time_zones_info`, `extract`, `format`, `move`, `replace`, `to`, `week`, `weekday`, `yday` and `zone` functions.

### 0.0.26

Update syntax highlighting with `randstr` and `join` function.

### 0.0.25

Update syntax highlighting with `is_closure` function.

### 0.0.24

Update syntax highlighting with renamed functions (see https://github.com/thingsdb/ThingsDB/issues/93).

### 0.0.23

Update syntax highlighting with `split`, `trim`, `trim_let`, `trim_right`, `alt_raise`, `reverse`, `shift`, `unshift` and `replace` functions.

### 0.0.22

Update syntax highlighting with `rename_type`, `rename_enum` and `rename_procedure` functions.

### 0.0.21

Update syntax highlighting with `event_id` function.

### 0.0.20

Update syntax highlighting with `type_assert` function.

### 0.0.19

Update syntax highlighting with `emit` and `assign` function.

### 0.0.18

Update syntax highlighting with `enum` related functions.

### 0.0.17

Update syntax highlighting with the `def` function.

### 0.0.16

Fix highlighting of error functions.

### 0.0.15

Update syntax highlighting with the `restore` function.

### 0.0.14

Update syntax highlighting with support for Template Strings.

### 0.0.13

Update syntax highlighting with the `each` function.

### 0.0.12

Update syntax highlighting with the `range` function.

### 0.0.11

Update syntax highlighting with the `watch`, `unwatch`, `every` and `some` functions.

### 0.0.10

Update syntax highlighting with the `reduce` function.

### 0.0.9

Added support for regular expressions.

### 0.0.8

Added `rand`, `randint` and `choice` to the syntax.

### 0.0.7

Added syntax highlighting for ThingsDB `v0` language.

