### Logstash Syslog and Postfix Parser

This is a logstash pipeline, which was written to parse key/value pairs from syslog-formatted logs, with high fidelity for the Postfix application.  All parsing is done inline, without using a separate patterns file.  The result is messy to read, but demonstrates the power of regex in logstash filters. (I.E. Line 155)
