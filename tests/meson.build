test_exe = executable('starlet_serializer_tests',
  files(
    'image_parser_test.cpp',
    'mesh_parser_test.cpp',
    'parser_test.cpp',
    'scene_parser_test.cpp',
    'test_helpers.hpp',
    'image/bmp_parser_test.cpp',
    'image/tga_parser_test.cpp',
    'mesh/obj_parser_test.cpp',
    'mesh/ply_parser_test.cpp',
  ),
  dependencies : [starlet_serializer_dep, gtest_dep]
)

test('starlet-serializer tests', test_exe)
