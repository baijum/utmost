project('utmost', 'c',
        version: '0.1.0',
        default_options: [
          'buildtype=debugoptimized',
          'warning_level=1',
          'c_std=c99',
        ],
        meson_version : '>= 0.40.0',
        license: 'MIT')

src = ['main.c', 'parser.c', 'scanner.c', 'token.c']
exe = executable('utmost', src)
test('test', exe)
