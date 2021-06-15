# pfSense filterlog extractors

The pfSense 2.4.x extractors for Graylog 3 are no longer maintained.

The extractors for pfSense 2.5.x for Graylog 4 should be able to extract all fields from the filterlogs. Currently supports IPv4 and IPv6, TCP, UDP.
Make sure your pfSense logging configuration is set to BSD rfc3164 format.

When you create your input in Graylog, make sure you set override_source to the FQDN (or hostname or ip) of your pfSense box.
