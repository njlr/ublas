include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'ublas',
  header_only = True,
  header_namespace = 'boost/numeric/ublas',
  exported_headers = subdir_glob([
    ('include/boost/numeric/ublas', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
