licenses(['notice'])

ts_library(
    name = 'io-ts',
    srcs = glob(['src/*.ts']),
    module_name = 'io-ts',
    deps = [
        '//third_party/ts/fp-ts',
        '@npm//@types',
    ],
    tsconfig = ':tsconfig-bazel.json',
    visibility = ['//visibility:public'],
)
