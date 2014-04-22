project(PlaneWidgetExample2)

cmake_minimum_required(VERSION 2.8)

find_package(VTK REQUIRED)
include(${VTK_USE_FILE})

add_executable(PlaneWidgetExample2
  main.cxx
)

TARGET_LINK_LIBRARIES(PlaneWidgetExample2
  vtkWidgets
  vtkRendering
)