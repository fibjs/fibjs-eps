# console

module

## method

| API   |  Node.js v7   |     fibjs         |
|-------|---------------|-------------------|
|add||add (Array cfg)|
|add||add (Value cfg)|
|reset||reset ()|
|log||log (String fmt,...)|
|log|log([data][, ...args])|log (...)|
|debug||debug (String fmt,...)|
|debug||debug (...)|
|info||info (String fmt,...)|
|info|info([data][, ...args])|info (...)|
|notice||notice (String fmt,...)|
|notice||notice (...)|
|warn||warn (String fmt,...)|
|warn|warn([data][, ...args])|warn (...)|
|error||error (String fmt,...)|
|error| error([data][, ...args])|error (...)|
|crit||crit (String fmt,...)|
|crit||crit (...)|
|alert||alert (String fmt,...)|
|alert||alert (...)|
|dir|dir(obj[, options])|dir (Value obj)|
|time|time(label)|time (String label="time")|
|timeEnd|timeEnd(label)|timeEnd (String label="time")|
|trace|trace([message][, ...args])|trace (String label="trace")|
|assert|assert(value[, message][, ...args])|assert (Value value, String msg="")|
|print||print (String fmt,...)|
|print||print (...)|
|moveTo||moveTo (Integer row, Integer column)|
|hideCursor||hideCursor ()|
|showCursor||showCursor ()|
|clear||clear ()|
|keyDown||keyDown (String key, String modifier="")|
|keyDown||keyDown (String key, Array modifier)|
|keyUp||keyUp (String key, String modifier="")|
|keyUp||keyUp (String key, Array modifier)|
|keyTap||keyTap (String key, String modifier="")|
|keyTap||keyTap (String key, Array modifier)|
|typeString||typeString (String text)|
|moveMouse||moveMouse (Integer x, Integer y)|
|mouseUp||mouseUp (String button)|
|mouseDown||mouseDown (String button)|
|clickMouse||clickMouse (String button, Boolean dbclick=false)|
|readLine||String 	readLine (String msg="") async|

## property

|       property      |       Node.js v7     |   fibjs    |
|---------------------|----------------------|------------|
|||ALERT = 1|
|||FATAL = 0|
|||CRIT = 2|
|||ERROR = 3|
|||WARN = 4|
|||NOTICE = 5|
|||INFO = 6|
|||DEBUG = 7|
|||PRINT = 9|
|||NOTSET = 10|
|||static Integer 	loglevel|
|||static readonly Integer 	height|
|||static readonly TextColor 	colors|
|||static readonly Integer 	width|