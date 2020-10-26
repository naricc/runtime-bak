project(mono)

#set(subdirs eglib arch utils cil sgen metadata mini dis profiler)
set(subdirs mini profiler coregc)

foreach(dir ${subdirs})
  add_subdirectory(${dir})
endforeach()
