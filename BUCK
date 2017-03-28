include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'function-types',
  header_only = True,
  header_namespace = 'boost/function_types',
  exported_headers = subdir_glob([
    ('include/boost/function_types', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
