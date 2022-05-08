project('lang-learn', 'cpp',
  version : '0.0.1',
  default_options : ['warning_level=3',
                     'cpp_std=c++17'])

gnome = import('gnome')

resource_files = gnome.compile_resources(
  'as-resources', 'assets/resources.gresource.xml',
  source_dir: 'assets',
  c_name: 'as'
  )

deps = [
  dependency('gtkmm-4.0')
]

sources = [
  'src/main.cpp',
  'src/application.cpp',
  'src/window.cpp'
]
incdir = include_directories('include')

exe = executable('lang_learn', sources, resource_files,
  include_directories: incdir,
  dependencies: deps
)

test('basic', exe)
