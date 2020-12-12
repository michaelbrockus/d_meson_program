if get_option('with_tests').enabled()
    test_exe = executable('test-prog',
        files('test_cases.d'),
        d_args: '-Wmain',
        d_unittest: true,
        dependencies : [code_dep])

    test('Execute project tests', test_exe)
endif
