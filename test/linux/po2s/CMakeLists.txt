
set(SOURCES el3751_po2s.c)
add_executable(el3751_po2s ${SOURCES})
target_link_libraries(el3751_po2s soem)
install(TARGETS el3751_po2s DESTINATION bin)
