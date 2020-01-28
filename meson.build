project('boost-static', 'cpp',
        default_options : ['warning_level=3', 'cpp_std=c++17'],
        version: '1.0')

boost_dep = dependency('boost',
  modules: ['chrono'],
  static : true)

boost_static = executable('boost-static',
  ['main.cc'],
  dependencies : [boost_dep]
)

