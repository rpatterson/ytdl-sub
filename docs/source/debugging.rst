=========
Debugging
=========

TODO

As a lower-level tool


Debugging
---------

Debug Logs
^^^^^^^^^^

Run with ``--log-level debug`` to show all debug logs when running ytdl-sub.


Reproducing a Failing Subscription
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Subscriptions will dump their entire *compiled* yaml at the beginning of exeuction when
using ``--log-level debug``. This can be copy-pasted into the file
``resources/file_fixtures/repro.yaml``.

Running the test ``e2e.test_debug_repro.TestReproduce.test_debug_log_repro`` will fully
reproduce that subscription in order to debug it.

When running your configuration of ``ytdl-sub`` fails, isn't doing what you expected, or
there are other issues, examine its output for clues.

TODO
