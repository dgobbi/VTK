if(NOT VTK_OPENGL_HAS_OSMESA)
  add_test_python(TestFlyTo.py Rendering)
  add_test_python(TestStyleRubberBandZoom.py Rendering)
  add_test_python(TestInteractorStyleTerrain.py Rendering)
  add_test_python1(TestStyleBaseSpike.py Baseline/Rendering)
  add_test_python1(TestStyleJoystickActor.py Baseline/Rendering)
  add_test_python1(TestStyleJoystickCamera.py Baseline/Rendering)
  add_test_python1(TestStyleTerrain.py Baseline/Rendering)
  add_test_python1(TestStyleTrackballActor.py Baseline/Rendering)
  add_test_python1(TestStyleTrackballCamera.py Baseline/Rendering)
endif()
