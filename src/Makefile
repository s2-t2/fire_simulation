EXE = project
SRC = ../common/texture.cpp \
	  ../common/controls.cpp \
	  ../common/objloader.cpp \
	  ../common/quaternion_utils.cpp \
	  ../common/shader.cpp \
	  ../common/tangentspace.cpp \
	  ../common/text2D.cpp \
	  ../common/vboindexer.cpp \
	  ../external/imgui/imgui.cpp \
	  ../external/imgui/imgui_impl_glfw_gl3.cpp \
	  ../external/imgui/imgui_demo.cpp \
	  ../external/imgui/imgui_draw.cpp \
		  	  ./$(EXE).cpp

all:
		g++ --std=c++11 -o $(EXE) $(SRC) \
			-I../common/ \
			-I../external/AntTweakBar-1.16/include/ \
			-I../external/assimp-3.0.1270/include/assimp/ \
			-I../external/bullet-2.81-rev2613 \
			-I../external/glew-1.13.0/include/GL/ \
			-I../external/glfw-3.1.2/include/GLFW/ \
			-I../external/glm-0.9.7.1i/glm/ \
			-I../external/glm-0.9.7.1/glm/gtx/ \
			-I../external/imgui/ \
			-I../external/rpavlik-cmake-modules-fe2273 \
			-L /usr/lib/x86_64-linux-gnu/libglfw.so.3.1 \
			-lGL -lGLEW -lGLU -lglut -lglfw -lstdc++ -lGLU 

clean:
		rm $(EXE)

