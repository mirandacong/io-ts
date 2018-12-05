licenses(['notice'])

ts_library(
    name = 'io-ts',
    srcs = glob(['src/*.ts']),
    deps = [
        '@npm//@types',
        label('../fp-ts'),
    ],
    tsconfig = ':tsconfig.json',
    visibility = ['//visibility:public'],
)
