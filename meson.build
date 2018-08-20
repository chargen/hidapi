project('hidapi', 'c')

inc = include_directories('hidapi')

cc = meson.get_compiler('c')
dep = cc.find_library('setupapi')

hidapi_lib = shared_library('hidapi', 'windows/hid.c', include_directories : inc, dependencies : dep)
hidapi = declare_dependency(include_directories: inc, link_with : hidapi_lib)
