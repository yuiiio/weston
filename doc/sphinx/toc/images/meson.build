# Sphinx does not know look for these files in the source directory, so
# they must be copied to the build directory.
files = [
	'ivi-shell.png',
]

foreach file : files
	configure_file(input: file, output: file, copy: true)
endforeach
