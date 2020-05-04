add_executable(SocialDistance WIN32 MACOSX_BUNDLE
    ../Framework/sampleapp.cpp
	app.cpp
	crowd.cpp
	main.cpp
)

target_link_libraries(SocialDistance Horde3D Horde3DUtils ${GLFW_LIBRARIES})

add_dependencies(SocialDistance SampleFramework)
