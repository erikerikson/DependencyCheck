CMake Analyzer
==============

OWASP dependency-check includes an analyzer that will scan CMake project
configuration files. The analyzer will collect as much information it can
about the project. The information collected is internally referred to as
evidence and is grouped into vendor, product, and version buckets. Other
analyzers later use this evidence to identify any Common Platform Enumeration
(CPE) identifiers that apply.

File names scanned: CMakeLists.txt, \*.cmake
