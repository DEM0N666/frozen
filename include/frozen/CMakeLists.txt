target_sources(frozen INTERFACE
  $<BUILD_INTERFACE:
    ${CMAKE_CURRENT_LIST_DIR}/algorithm.h
    ${CMAKE_CURRENT_LIST_DIR}/map.h
    ${CMAKE_CURRENT_LIST_DIR}/random.h
    ${CMAKE_CURRENT_LIST_DIR}/set.h
    ${CMAKE_CURRENT_LIST_DIR}/string.h
    ${CMAKE_CURRENT_LIST_DIR}/unordered_map.h
    ${CMAKE_CURRENT_LIST_DIR}/unordered_set.h
    ${CMAKE_CURRENT_LIST_DIR}/bits/algorithms.h
    ${CMAKE_CURRENT_LIST_DIR}/bits/basic_types.h
    ${CMAKE_CURRENT_LIST_DIR}/bits/elsa.h
    ${CMAKE_CURRENT_LIST_DIR}/bits/pmh.h>
  $<INSTALL_INTERFACE:
    include/frozen/algorithm.h
    include/frozen/map.h
    include/frozen/random.h
    include/frozen/set.h
    include/frozen/string.h
    include/frozen/unordered_map.h
    include/frozen/unordered_set.h
    include/frozen/bits/algorithms.h
    include/frozen/bits/basic_types.h
    include/frozen/bits/elsa.h
    include/frozen/bits/pmh.h>)
