project('libdatrie-oottest', 'c')

libdatrie_dep = dependency('datrie-0.2', required : false)
if not libdatrie_dep.found()
	libdatrie_dep = subproject('libdatrie').get_variable('libdatrie_dep')
endif

exe = executable(
	'test_walk',
	
	'test_walk.c',
	'utils.c',
	
	dependencies : libdatrie_dep,
)
test('walk', exe)
