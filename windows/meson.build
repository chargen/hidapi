project('hidapi', 'c')

inc = include_directories('../hidapi')

cc = meson.get_compiler('c')
dep = cc.find_library('setupapi')

shared_library('hidapi', 'hid.c', include_directories : inc, dependencies : dep)
