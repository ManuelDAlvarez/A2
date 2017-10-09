# A2

A2 ON

setHeader	Pragma:akamai-x-cache-on, akamai-x-get-cache-key, akamai-x-get-true-cache-key, x-akamai-a2-trace, akamai-x-ro-trace
setHeader	X-Akamai-RO:on
setHeader	x-akamai-a2-enable:
navigate	https://www.akamai.com/

A2 Off

setHeader	Pragma:akamai-x-cache-on, akamai-x-get-cache-key, akamai-x-get-true-cache-key, x-akamai-a2-trace, akamai-x-ro-trace
setHeader	X-Akamai-RO:off
setHeader	x-akamai-a2-disable:
navigate	https://www.akamai.com/
