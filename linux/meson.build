project('hidapi', 'c')

inc = include_directories('../hidapi')

dep = dependency('libudev')

shared_library('hidapi-hidraw', 'hid.c', include_directories : inc, dependencies : dep)
