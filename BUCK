include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'restbed',
  header_namespace = '',
  headers = subdir_glob([
    ('source', 'corvusoft/restbed/**/*.hpp'),
  ]),
  exported_headers = subdir_glob([
    ('source', 'restbed'),
    ('source', 'corvusoft/restbed/**/*.hpp'),
  ]),
  srcs = glob([
    'source/**/*.cpp',
  ]),
  compiler_flags = [],
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
