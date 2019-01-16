load('//:subdir_glob.bzl', 'subdir_glob')

prebuilt_cxx_library(
  name = 'variant',
  header_namespace = 'mapbox',
  header_only = True,
  exported_headers = subdir_glob([
    ('include/mapbox', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
)
