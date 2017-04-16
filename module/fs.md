# fs

module

## method

| API | Node.js v7 |fibjs |
|-----|-------|--------|
| access            |	access(path[, mode], callback)              |                                        |
| accessSync        |	accessSync(path[, mode])                    |                                        | 
| appendFile        |	appendFile(file, data[, options], callback) |                                        | 
| appendFileSync    |	appendFileSync(file, data[, options])       |                                        | 
| chmod             | chmod(path, mode, callback)                 | chmod (path, mode) async               |
| chmodSync         | chmodSync(path, mode)|chmodSync (path, mode)|                                        |
| chown             |	chown(path, uid, gid, callback)             |                                        |
| chownSync         |	chownSync(path, uid, gid)                   |                                        |
| close             |	close(fd, callback)                         |                                        |
| closeSync         |	closeSync(fd)                               |                                        |
| createReadStream  |	createReadStream(path[, options])           |                                        |
| createWriteStream |	createWriteStream(path[, options])          |                                        |
| copy              |	                                            | copy (from, to) async                  |
| exists            |                                             | Boolean exists (path) async            |
| existsSync        | existsSync(path)                            | Boolean existsSync (path)              |
| fchmod            |	fchmod(fd, mode, callback)                  |                                        |
| fchmodSync        |	fchmodSync(fd, mode)                        |                                        |
| fchown            |	fchown(fd, uid, gid, callback)              |                                        |
| fchownSync        |	fchownSync(fd, uid, gid)                    |                                        |
| fdatasync         |	fdatasync(fd, callback)                     |                                        |
| fdatasyncSync     |	fdatasyncSync(fd)                           |                                        |
| fstat             |	fstat(fd, callback)                         |                                        |
| fstatSync         |	fstatSync(fd)                               |                                        |
| fsync             |	fsync(fd, callback)                         |                                        |
| fsyncSync         |	fsyncSync(fd)                               |                                        |
| ftruncate         |	ftruncate(fd, len, callback)                |                                        |
| ftruncateSync     |	ftruncateSync(fd, len)                      |                                        |
| futimes           |	futimes(fd, atime, mtime, callback)         |                                        |
| futimesSync       |	futimesSync(fd, atime, mtime)               |                                        |
| lchmod            |	lchmod(path, mode, callback)                |                                        |
| lchmodSync        |	lchmodSync(path, mode)                      |                                        |
| lchown            |	lchown(path, uid, gid, callback)            |                                        |
| lchownSync        |	lchownSync(path, uid, gid)                  |                                        |
| link              |	link(existingPath, newPath, callback)       |                                        |
| linkSync          |	linkSync(existingPath, newPath)             |                                        |
| lstat             |	lstat(path, callback)                       |                                        |
| lstatSync         |	lstatSync(path)                             |                                        |
| mkdir             | mkdir(path[, mode], callback)               |mkdir (path, mode=0777) async           |
| mkdirSync         | mkdirSync(path[, mode])                     |mkdirSync (path, mode=0777)             |
| mkdtemp           |	mkdtemp(prefix[, options], callback)        |                                        |
| mkdtempSync       |	mkdtempSync(prefix[, options])              |                                        |
| open              | open(path, flags[, mode], callback)         |open (fname, flags="r") async           |
| openSync          | openSync(path, flags[, mode])               |openSync (fname, flags="r")             |
| openTextStream    |                                             | openTextStream (fname, flags="r") async|
| read              |	read(fd, buffer, offset, length, position, callback)  |                              | 
| readSync          |	readSync(fd, buffer, offset, length, position) |                                     | 
| readdir           | readdir(path[, options], callback)          | List readdir (path) async              | 
| readdirSync       | readdirSync(path[, options])                | List readdirSync (path)                |
| readFile          | readFile(file[, options], callback)         | Buffer readFile (fname) async          |
| readFileSync      | readFileSync(file[, options])               | Buffer readFileSync (fname)            |
| readLines         |                                             | Array readLines (fname, maxlines=-1)   |
| readlink          |	readlink(path[, options], callback)         |                                        |
| readlinkSync      |	readlinkSync(path[, options])               |                                        |
| realpath          |	realpath(path[, options], callback)         |                                        |
| realpathSync      |	realpathSync(path[, options])               |                                        |
| readTextFile      |                                             | String readTextFile (fname) async      |
| rename            |	rename(oldPath, newPath, callback)          | rename (from, to) async                |
| renameSync        |	renameSync(oldPath, newPath)                | renameSync (from, to)                  |
| rmdir             |	rmdir(path, callback)                       | rmdir (path) async                     |
| rmdirSync         |	rmdirSync(path)                             | rmdirSync (path)                       |
| stat              | stat(path, callback)                        | Stat 	stat (path) async                |
| statSync          | statSync(path)                              | Stat 	statSync (path)                  |
| symlink           |	symlink(target, path[, type], callback)     |                                        |
| symlinkSync       |	symlinkSync(target, path[, type])           |                                        |
| truncate          |	truncate(path, len, callback)               |                                        |
| truncateSync      |	truncateSync(path, len)                     |                                        |
| unlink            | unlink(path, callback)                      | unlink (path) async                    |
| unlinkSync        | unlinkSync(path)                            | unlinkSync (path)                      |
| unwatchFile       |	unwatchFile(filename[, listener])           |                                        |
| utimes            |	utimes(path, atime, mtime, callback)        |                                        |
| utimesSync        |	utimesSync(path, atime, mtime)              |                                        |
| watch             |	watch(filename[, options][, listener])      |                                        |
| watchFile         |	watchFile(filename[, options], listener)    |                                        |
| write             |	write(fd, buffer[, offset[, length[, position]]], callback) |                        |
| write             |	write(fd, string[, position[, encoding]], callback)|                                 |
| writeFile         |	writeFile(file, data[, options], callback)  |  writeFile (fname, data) async         |
| writeFileSync     |	writeFileSync(file, data[, options])        |  writeFileSync (fname, data)           |
| writeSync         |	writeSync(fd, buffer[, offset[, length[, position]]])   |                            |
| writeSync         |	writeSync(fd, string[, position[, encoding]])  |                                     |
| writeTextFile     |	                                            | writeTextFile (fname, txt) asyc        |

## property

| property | Node.js v7 |      fibjs         |
|----------|------------|--------------------|
|SEEK_SET  |            | const SEEK_SET = 0 |
|SEEK_CUR  |            | const SEEK_CUR = 1 |
|SEEK_END  |            | const SEEK_END = 2 |
|constants | constants  |                    |
|F_OK      | F_OK: 0    |                    |
|R_OK      | R_OK: 4    |                    |
|W_OK      | W_OK: 2    |                    |
|X_OK      | X_OK: 1    |                    |

`Node.js fs.constants:`
 
- O_RDONLY: 0
- O_WRONLY: 1
- O_RDWR: 2
- S_IFMT: 61440
- S_IFREG: 32768
- S_IFDIR: 16384
- S_IFCHR: 8192
- S_IFBLK: 24576
- S_IFIFO: 4096
- S_IFLNK: 40960
- S_IFSOCK: 49152
- O_CREAT: 512
- O_EXCL: 2048
- O_NOCTTY: 131072
- O_TRUNC: 1024
- O_APPEND: 8
- O_DIRECTORY: 1048576
- O_NOFOLLOW: 256
- O_SYNC: 128
- O_SYMLINK: 2097152
- O_NONBLOCK: 4
- S_IRWXU: 448
- S_IRUSR: 256
- S_IWUSR: 128
- S_IXUSR: 64
- S_IRWXG: 56
- S_IRGRP: 32
- S_IWGRP: 16
- S_IXGRP: 8
- S_IRWXO: 7
- S_IROTH: 4
- S_IWOTH: 2
- S_IXOTH: 1
- F_OK: 0
- R_OK: 4
- W_OK: 2
- X_OK: 1
