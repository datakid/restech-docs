.. _java:

====
Java
====

Java is installed as part of the Operating System but we would strongly recommend against using that version - we cannot guarantee scientific reproducibility with that version. Please use the java modules. 

Each Java module sets 

::
    
    _JAVA_TOOL_OPTIONS -Xmx1g

This sets the heap memory to 1GB. If you need more, set the environment variable _JAVA_OPTIONS which overrides _JAVA_TOOL_OPTIONS

::

    export _JAVA_OPTIONS -Xmx5g

