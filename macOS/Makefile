imgui:
	g++ src/imguiTest.cpp src/imgui/imgui_impl_vulkan.cpp src/imgui/imgui_impl_glfw.cpp src/imgui/imgui.cpp src/imgui/imgui_demo.cpp src/imgui/imgui_draw.cpp src/imgui/imgui_tables.cpp src/imgui/imgui_widgets.cpp --std=c++17 -I./include/ -I${VULKAN_SDK}/include/ -Wl,-rpath,../lib -L./lib -L${VULKAN_SDK}/lib/ -lglfw.3 -lvulkan.1 -lvulkan.1.3.236 -o ./build/imguiTest
helloTriangle:
	g++ src/hello_triangle.cpp --std=c++17 -I./include/ -I${VULKAN_SDK}/include/ -Wl,-rpath,../lib -L./lib -L${VULKAN_SDK}/lib/ -lglfw.3 -lvulkan.1 -lvulkan.1.3.236 -o ./build/helloTriangle
logVulkan:
	g++ src/loggingVulkan.cpp src/Utils.cpp --std=c++17 -I./include/ -I${VULKAN_SDK}/include/ -Wl,-rpath,../lib -L./lib -L${VULKAN_SDK}/lib/ -lglfw.3 -lvulkan.1 -lvulkan.1.3.236 -o ./build/loggingVulkan
clean:
	rm ./build/imguiTest
	rm ./build/helloTriangle
	rm ./build/loggingVulkan
