# ImGui-docking-XP
A variant of dockable ImGui for Visual Studio 2010 and Windows XP.
Based on version 1.89.1 WIP (18902)


Tested and confirmed to compile Under Visual Studio 2010 SP1:
> 1. example_win32_directx9
> 2. example_glfw_opengl2


Link to original branch:
https://github.com/ocornut/imgui/tree/docking

Main modifications:
> * Downgraded some enums (ImDrawFlags)
> * Downgraded some structs in imgui.h (ImRect, ImVec1, ImVec2, ImVec2, ImVec2ih, ImVec4, ImColor)
> * Commented out ImFui_ImplWin32_EnableAlphaCompositing, Shcore.lib, dwmapi.lib and DPI functionality
> * Downgraded ImGui::NavUpdate method to use a conventional for loop
> * Downgraded ImGui::DockNodeMoveWindows method to use a conventional for loop

Be sure to use this at your own risk, as I am not the original author of this User Interface package. I made this for my personal use and decided to share, if anyone wants ImGui running under Windows XP!
