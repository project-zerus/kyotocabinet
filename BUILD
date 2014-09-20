cc_library(
  name = 'kyotocabinet',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kccachedb.cc',
    'kccompare.cc',
    'kccompress.cc',
    'kcdb.cc',
    'kcdbext.cc',
    'kcdirdb.cc',
    'kcfile.cc',
    'kchashdb.cc',
    'kclangc.cc',
    'kcmap.cc',
    'kcplantdb.cc',
    'kcpolydb.cc',
    'kcprotodb.cc',
    'kcregex.cc',
    'kcstashdb.cc',
    'kctextdb.cc',
    'kcthread.cc',
    'kcutil.cc',
  ],
  deps = [
    '#pthread',
    '//thirdparty/lzo:lzo',
    '//zlib:zlib',
  ],
)

cc_binary(
  name = 'kcutiltest',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kcutiltest.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kcprototest',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kcprototest.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kcstashtest',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kcstashtest.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kccachetest',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kccachetest.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kcgrasstest',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kcgrasstest.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kchashtest',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kchashtest.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kctreetest',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kctreetest.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kcdirtest',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kcdirtest.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kcforesttest',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kcforesttest.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kcpolytest',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kcpolytest.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kclangctest',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kclangctest.c',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kcutilmgr',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kcutilmgr.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kchashmgr',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kchashmgr.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kctreemgr',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kctreemgr.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kcdirmgr',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kcdirmgr.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kcforestmgr',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kcforestmgr.cc',
  ],
  deps = ':kyotocabinet',
)

cc_binary(
  name = 'kcpolymgr',
  extra_cppflags = [
    '-Wno-float-equal',
  ],
  srcs = [
    'kcpolymgr.cc',
  ],
  deps = ':kyotocabinet',
)
