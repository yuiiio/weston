# you need to add here any files you add to the toc directory as well
files = [
	'kiosk-shell.rst',
	'ivi-shell.rst',
	'running-weston.rst',
	'libweston.rst',
	'test-suite.rst',
	'test-suite-api.rst',
]

foreach file : files
	configure_file(input: file, output: file, copy: true)
endforeach

subdir('images')
subdir('libweston')
