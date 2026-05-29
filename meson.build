project('cLDtk', 'c')

cldtk_src = files(
  'cLDtk.c',
  'parson.c',
)

cldtk_inc = include_directories('.')

cldtk_lib = library(
  'cLDtk',
  cldtk_src,
  include_directories: [cldtk_inc],
)

cldtk_dep = declare_dependency(
  link_with: cldtk_lib,
  include_directories: [cldtk_inc],
)
