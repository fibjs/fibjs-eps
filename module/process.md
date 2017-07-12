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
| hrtime      | hrtime([time])                       | Array hrtime(Array diff = [])               |
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

| property  | Node.js v7 |           fibjs          |
|-----------|------------|--------------------------|
|arch       | arch       | readonly String arch     |
|argv       | argv       | readonly Array argv      |
|argv0      | argv0      |                          |
|channel    | channel    |                          |
|config     | config     |                          |
|connected  | connected  |                          |
|env        | env        | readonly Object env      |
|execArgv   | execArgv   | readonly Array execArgv  |
|execPath   | execPath   | readonly String execPath |
|exitCode   | exitCode   |                          |
|mainModule | mainModule |                          |
|pid        | pid        |                          |
|platform   | platform   | readonly String platform |
|release    | release    |                          |
|stderr     | stderr     |                          |
|stdin      | stdin      |                          |
|stdout     | stdout     |                          |
|title      | title      |                          |
|version    | version    | readonly String version  |
|versions   | versions   |                          |
|connected  | connected  |                          |

### Event

|         Event     |      Node.js v7    |  fibjs |
|-------------------|--------------------|--------|
|beforeExit         | beforeExit         |        |
|disconnect         | disconnect         |        |
|exit               | exit               |        |
|message            | message            |        |
|rejectionHandled   | rejectionHandled   |        |
|uncaughtException  | uncaughtException  |        |
|unhandledRejection | unhandledRejection |        |
|warning            | warning            |        |
|Signal             | Signal             |        |
