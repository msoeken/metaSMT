if( Boost_PYTHON_FOUND )
  add_subdirectory(python)
else ()
  message(STATUS "skipping python bindings because Boost Python is unavailable")
endif()
