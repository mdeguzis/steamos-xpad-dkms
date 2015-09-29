#minimum cmake version
cmake_minimum_required (VERSION 2.8.11)

#project name
project (steamos-xpad-dkms)

# Recurse into subdirectory "source". This does not actually
# cause another cmake executable to run. The same process will walk through
# the project's entire directory structure.
add_subdirectory (source)

#install documentation
install (FILES AUTHORS README DESTINATION /usr/share/doc/steamos-xpad-dkms
