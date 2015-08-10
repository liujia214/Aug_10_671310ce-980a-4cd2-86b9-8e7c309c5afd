HTTP request:method/verb,url,header,body

HTTP response:status code,header,body

Process Event:

a.loadstart once the send() execute
b.process once response received
c.abort
d.timeout
e.error
f.load
g.loadend

3 properties:
a.total:total size
b.loaded:has transferred size
c.lengthComputable:true if the content length is known



question:

1.encodeURIComponent(value.replace(' ','+'));