.. _release-notes:

#############
Release Notes
#############

7.0.0
=====

Features
--------
* Added a new API in all bindings that can be used to get a list of split points that will split the given range into (roughly) equally sized chunks. `(PR #3394) <https://github.com/apple/foundationdb/pull/3394>`_


Performance
-----------

* Increased performance of dr_agent when copying the mutation log. The ``COPY_LOG_BLOCK_SIZE``, ``COPY_LOG_BLOCKS_PER_TASK``, ``COPY_LOG_PREFETCH_BLOCKS``, ``COPY_LOG_READ_AHEAD_BYTES`` and ``COPY_LOG_TASK_DURATION_NANOS`` knobs can be set. `(PR 3436) <https://github.com/apple/foundationdb/pull/3436>`_

Reliability
-----------



Fixes
-----



Status
------



Bindings
--------
* Python: The function ``get_estimated_range_size_bytes`` will now throw an error if the ``begin_key`` or ``end_key`` is ``None``. `(PR #3394) <https://github.com/apple/foundationdb/pull/3394>`_
* C: Added a function, ``fdb_database_reboot_worker``, to reboot or suspend the specified process. `(PR #4094) <https://github.com/apple/foundationdb/pull/4094>`_

Other Changes
-------------

Earlier release notes
---------------------
* :doc:`6.3 (API Version 630) </release-notes/release-notes-630>`
* :doc:`6.2 (API Version 620) </release-notes/release-notes-620>`
* :doc:`6.1 (API Version 610) </release-notes/release-notes-610>`
* :doc:`6.0 (API Version 600) </release-notes/release-notes-600>`
* :doc:`5.2 (API Version 520) </release-notes/release-notes-520>`
* :doc:`5.1 (API Version 510) </release-notes/release-notes-510>`
* :doc:`5.0 (API Version 500) </release-notes/release-notes-500>`
* :doc:`4.6 (API Version 460) </release-notes/release-notes-460>`
* :doc:`4.5 (API Version 450) </release-notes/release-notes-450>`
* :doc:`4.4 (API Version 440) </release-notes/release-notes-440>`
* :doc:`4.3 (API Version 430) </release-notes/release-notes-430>`
* :doc:`4.2 (API Version 420) </release-notes/release-notes-420>`
* :doc:`4.1 (API Version 410) </release-notes/release-notes-410>`
* :doc:`4.0 (API Version 400) </release-notes/release-notes-400>`
* :doc:`3.0 (API Version 300) </release-notes/release-notes-300>`
* :doc:`2.0 (API Version 200) </release-notes/release-notes-200>`
* :doc:`1.0 (API Version 100) </release-notes/release-notes-100>`
* :doc:`Beta 3 (API Version 23) </release-notes/release-notes-023>`
* :doc:`Beta 2 (API Version 22) </release-notes/release-notes-022>`
* :doc:`Beta 1 (API Version 21) </release-notes/release-notes-021>`
* :doc:`Alpha 6 (API Version 16) </release-notes/release-notes-016>`
* :doc:`Alpha 5 (API Version 14) </release-notes/release-notes-014>`
