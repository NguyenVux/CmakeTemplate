macro(add_libs LIBS_FOLDER)
	add_subdirectory(${LIBS_FOLDER})
    set(LIB_TARGETS ${global_list} ${parameter} PARENT_SCOPE)
endmacro()

add_libs("MacroHardGameEngine")