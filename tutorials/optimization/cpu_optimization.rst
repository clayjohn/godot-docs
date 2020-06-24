.. _doc_cpu_optimization:

CPU Optimizations
=================

Introduction
~~~~~~~~~~~~


Profilers
~~~~~~~~~

Profilers generally allow you make a timing run of your program (or sections of it), then provide results telling you what percentage of time was spent in different functions and areas, and how often functions were called.

Godot profiler screenshot

Callgrind screenshot

This can be very useful both to identify bottlenecks and to measure the results of your improvements. Sometimes attempts to improve performance can backfire and lead to slower performance, so always use profiling and timing to guide your efforts.
