code_lib = static_library('code_lib', files('program.d'),
    include_directories: '.',
    install: true)

code_dep = declare_dependency(
    link_with: code_lib,
    include_directories: '.')

executable('prog', files('main.d'), dependencies: code_dep, install: true)
