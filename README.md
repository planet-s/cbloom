A concurrent implementation of Bloom filters.

Bloom filters is a simple data structure, which is used in many different situations. It can
neatly solve certain problems heaurustically without need for extreme memory usage.

This implementation is fairly standard, except that it uses atomic integers to work
concurrently.
