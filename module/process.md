# process

module

## method

|     API     |               Node.js v7             |                    fibjs                    |
|-------------|--------------------------------------|---------------------------------------------|
| abort       | abort()                              |                                             |
| chdir       | chdir(directory)                     | chdir(directory)                            |
| cpuUsage    | cpuUsage([previousValue])            |                                             |
| cwd         | cwd()                                | String cwd()                                |
| disconnect  | disconnect()                         |                                             |
| emitWarning | emitWarning(warning[, name][, ctor]) |                                             |
| exit        | exit([code])                         | exit(Integer code)                          |
| getegid     | getegid()                            |                                             |
| geteuid     | geteuid()                            |                                             |
| getgid      | getgid()                             |                                             |
| getgroups   | getgroups()                          |                                             |
| getuid      | getuid()                             |                                             |
| hrtime      | hrtime([time])                       |                                             |
| initgroups  | initgroups(user, extra_group)        |                                             |
| kill        | kill(pid[, signal])                  |                                             |
| memoryUsage | memoryUsage()                        | Object memoryUsage()                        |
| nextTick    | nextTick(callback[, ...args])        | nextTick(func,...)                          |
| send        | send(message[, sendHandle[, options]][, callback])|                                |
| setegid     | setegid(id)                          |                                             |
| seteuid     | seteuid(id)                          |                                             |
| setgid      | setgid(id)                           |                                             |
| setgroups   | setgroups(groups)                    |                                             |
| setuid      | setuid(id)                           |                                             |
| umask       | umask([mask])                        | Integer umask (Integer mask)                |
| umask       |                                      | Integer umask (String mask)                 |
| umask       |                                      | Integer umask ()                            |
| uptime      | uptime()                             | Number uptime()                             |
| open        |                                      | SubProcess open(command, args=[], opts={})  |
| open        |                                      | SubProcess open(command, opts={})           |
| start       |                                      | SubProcess start(command, args=[], opts={}) |
| start       |                                      | SubProcess start(command, opts={})          |
| run         |                                      | Integer run (command, args=[], opts={})     |
| run         |                                      | Integer run (command, opts={})              |

## property

| property | Node.js v7 |           fibjs          |
|----------|------------|--------------------------|
|          | arch       | readonly String arch     |
|          | argv       | readonly Array argv      |
|          | argv0      |                          |
|          | channel    |                          |
|          | config     |                          |
|          | connected  |                          |
|          | env        | readonly Object env      |
|          | execArgv   | readonly Array execArgv  |
|          | execPath   | readonly String execPath |
|          | exitCode   |                          |
|          | mainModule |                          |
|          | pid        |                          |
|          | platform   | readonly String platform |
|          | release    |                          |
|          | stderr     |                          |
|          | stdin      |                          |
|          | stdout     |                          |
|          | title      |                          |
|          | version    | readonly String version  |
|          | versions   |                          |
|          | connected  |                          |

### Event

| Event |      Node.js v7    |  fibjs |
|-------|--------------------|--------|
|       | beforeExit         |        |
|       | disconnect         |        |
|       | exit               |        |
|       | message            |        |
|       | rejectionHandled   |        |
|       | uncaughtException  |        |
|       | unhandledRejection |        |
|       | warning            |        |
|       | Signal             |        |
