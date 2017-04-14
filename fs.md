# fs

## method

| API | fibjs | Node.js|
|-----|-------|--------|
|access |	|fs.access(path[, mode], callback) |
|accessSync |	| fs.accessSync(path[, mode])|
|appendFile |	| fs.appendFile(file, data[, options], callback)|
|appendFileSync |	| fs.appendFileSync(file, data[, options])|
|chmod|	chmod (String path, Integer mode) async| fs.chmod(path, mode, callback)|
|chmodSync|	chmodSync (String path, Integer mode)| fs.chmodSync(path, mode)|
|chown |	| fs.chown(path, uid, gid, callback)|
|chownSync |	| fs.chownSync(path, uid, gid)|
|close |	| fs.close(fd, callback)|
|closeSync |	| fs.closeSync(fd)|
|createReadStream |	| fs.createReadStream(path[, options])|
|createWriteStream |	| fs.createWriteStream(path[, options])|
|copy|	copy (String from, String to) async| |
|exists | Boolean 	exists (String path) async | fs.exists(path, callback)|
|existsSync | Boolean 	existsSync (String path) | fs.existsSync(path)|
|fchmod |	| fs.fchmod(fd, mode, callback)|
|fchmodSync |	| fs.fchmodSync(fd, mode)|
|fchown |	| fs.fchown(fd, uid, gid, callback)|
|fchownSync |	| fs.fchownSync(fd, uid, gid)|
|fdatasync |	| fs.fdatasync(fd, callback)|
|fdatasyncSync |	| fs.fdatasyncSync(fd)|
|fstat |	| fs.fstat(fd, callback)|
|fstatSync |	| fs.fstatSync(fd)|
|fsync |	| fs.fsync(fd, callback)|
|fsyncSync |	| fs.fsyncSync(fd)|
|ftruncate |	| fs.ftruncate(fd, len, callback)|
|ftruncateSync |	| fs.ftruncateSync(fd, len)|
|futimes |	| fs.futimes(fd, atime, mtime, callback)|
|futimesSync |	| fs.futimesSync(fd, atime, mtime)|
|lchmod |	| fs.lchmod(path, mode, callback)|
|lchmodSync |	| fs.lchmodSync(path, mode)|
|lchown |	| fs.lchown(path, uid, gid, callback)|
|lchownSync |	| fs.lchownSync(path, uid, gid)|
|link |	| fs.link(existingPath, newPath, callback)|
|linkSync |	| fs.linkSync(existingPath, newPath)|
|lstat |	| fs.lstat(path, callback)|
|lstatSync |	| fs.lstatSync(path)|
|mkdir |mkdir (String path, Integer mode=0777) async  | fs.mkdir(path[, mode], callback)|
|mkdirSync |mkdirSync (String path, Integer mode=0777)  | fs.mkdirSync(path[, mode])|
|mkdtemp |	| fs.mkdtemp(prefix[, options], callback)|
|mkdtempSync |	| fs.mkdtempSync(prefix[, options])|
|open| SeekableStream 	open (String fname, String flags="r") async| fs.open(path, flags[, mode], callback)|
|openSync| SeekableStream 	openSync (String fname, String flags="r")| fs.openSync(path, flags[, mode])|
|openTextStream| BufferedStream 	openTextStream (String fname, String flags="r") async| |
|read |	| fs.read(fd, buffer, offset, length, position, callback)|
|readSync |	| fs.readSync(fd, buffer, offset, length, position)|
| |	| |
| |	| |
|readdir| List 	readdir (String path) async| fs.readdir(path[, options], callback)|
|readdirSync| List 	readdirSync (String path)| fs.readdirSync(path[, options])|
|readFile| Buffer 	readFile (String fname) async| fs.readFile(file[, options], callback)|
|readFileSync| Buffer 	readFileSync (String fname)| fs.readFileSync(file[, options])|
|readLines| Array 	readLines (String fname, Integer maxlines=-1)| |
|readlink |	| fs.readlink(path[, options], callback)|
|readlinkSync |	| fs.readlinkSync(path[, options])|
|realpath |	| fs.realpath(path[, options], callback)|
|realpathSync |	| fs.realpathSync(path[, options])|
|readTextFile| String 	readTextFile (String fname) async| |
|rename|	rename (String from, String to) async| fs.rename(oldPath, newPath, callback)|
|renameSync|	renameSync (String from, String to)| fs.renameSync(oldPath, newPath)|
|rmdir|	rmdir (String path) async| fs.rmdir(path, callback)|
|rmdirSync|	rmdirSync (String path)| fs.rmdirSync(path)|
|stat| Stat 	stat (String path) async| fs.stat(path, callback)|
|statSync| Stat 	statSync (String path)| fs.statSync(path)|
|symlink |	| fs.symlink(target, path[, type], callback)|
|symlinkSync |	| fs.symlinkSync(target, path[, type])|
|truncate |	| fs.truncate(path, len, callback)|
|truncateSync |	| fs.truncateSync(path, len)|
|unlink |unlink (String path) async  | fs.unlink(path, callback)|
|unlinkSync |unlinkSync (String path) | fs.unlinkSync(path)|
|unwatchFile |	| fs.unwatchFile(filename[, listener])|
|utimes |	| fs.utimes(path, atime, mtime, callback)|
|utimesSync |	| fs.utimesSync(path, atime, mtime)|
|watch |	| fs.watch(filename[, options][, listener])|
|watchFile |	| fs.watchFile(filename[, options], listener)|
|write |	| fs.write(fd, buffer[, offset[, length[, position]]], callback)|
|write |	| fs.write(fd, string[, position[, encoding]], callback)|
|writeFile|	writeFile (String fname, Buffer data) async| fs.writeFile(file, data[, options], callback)|
|writeFileSync|	writeFileSync (String fname, Buffer data)| fs.writeFileSync(file, data[, options])|
|writeSync |	| fs.writeSync(fd, buffer[, offset[, length[, position]]])|
|writeSync |	| fs.writeSync(fd, string[, position[, encoding]])|
|writeTextFile|	writeTextFile (String fname, String txt) asy| |



## property

| property | fibjs | Node.js|
|-----|-------|--------|
| | const 	SEEK_SET = 0 | |
| | const 	SEEK_CUR = 1 | |
| | const 	SEEK_END = 2 | |
| |                      | constants|
| |                      | F_OK: 0|
| |                      | R_OK: 4|
| |                      | W_OK: 2|
| |                      | X_OK: 1|

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
