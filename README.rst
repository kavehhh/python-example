===========
MicroDonuts
===========

To run server.py:

``ls-trace-run python walkthrough/server.py``

To run other-server.py:

First..

``export DD_TRACE_AGENT_URL=https://ingest.lightstep.com:443``

``export DD_TRACE_GLOBAL_TAGS="lightstep.service_name:lightstep-py,lightstep.access_token:<access-token>"``

Then..

``ls-trace-run python walkthrough/other-server.py``
