hello.html: hello.c html_template/shell_minimal.html
	emcc -o hello.html hello.c --shell-file html_template/shell_minimal.html -s NO_EXIT_RUNTIME=1 -s "EXPORTED_RUNTIME_METHODS=['ccall']"
