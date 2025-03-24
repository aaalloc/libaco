project(
    'libaco',
    'c',
    version: '1.0',
    default_options: ['warning_level=2', 'optimization=2'],
)

libaco_sources  = [
    'acosw.S',
    'aco.c',
]

libaco = static_library(
    'aco',
    libaco_sources,
)

libaco_dep = declare_dependency(
    include_directories: include_directories('.'),
    link_with: libaco,
)