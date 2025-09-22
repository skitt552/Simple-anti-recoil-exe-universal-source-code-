Skitzs Anti Recoil

Overview

Skitzs Anti Recoil is a small utility that allows you to:
	•	Pull the mouse down, left, or right with adjustable strength and smoothness.
	•	Use a rapid-fire toggle that clicks repeatedly while the main hotkey is held down.
	•	Set required ADS, which makes mouse pulling only active when both left and right mouse buttons are pressed simultaneously.
	•	Save and load named configuration files for different settings.
	•	Customize hotkeys for main pulling, toggle, and rapid-fire functionality.
	•	Displays a watermark (“Skitzs Anti Recoil”) in the GUI for branding.

The program is fully GUI-driven using ImGui and works with DirectX 11.

⸻

Features
	1.	Mouse Pulling
	•	Adjustable pull down, pull left, pull right, and smoothness sliders.
	•	Can be toggled on/off with a hotkey.
	•	Optionally requires both mouse buttons pressed (Required ADS) for pulling to work.
	2.	Rapid Fire
	•	Toggle rapid-fire on/off with a hotkey.
	•	Only executes while the main mouse button is held down.
	•	Adjustable click speed via slider.
	3.	Configuration
	•	Save settings with a config name.
	•	Load saved configs from a dropdown list.
	•	Delete saved configs if no longer needed.
	4.	GUI
	•	Pink and black theme.
	•	Watermark: “Skitzs Anti Recoil”.
	•	Fully interactive sliders, buttons, and dropdown menus.

⸻

Requirements
	•	Windows 10 or later.
	•	Visual Studio 2019+ or equivalent with C++ Desktop Development workload.
	•	DirectX 11 SDK (usually included in Windows 10 SDK).
	•	ImGui library with DirectX 11 and Win32 bindings.

⸻

Compilation Instructions
	1.	Clone or copy the code into a folder, e.g., SkitzsAntiRecoil.
	2.	Create a new Visual Studio C++ Project
	•	Type: Windows Desktop Application (Console or Empty project).
	•	Add main.cpp (the code provided) to the project.
	3.	Add ImGui to the project
	•	Download ImGui from https://github.com/ocornut/imgui
	•	Include the following files in your project:
	•	imgui.cpp, imgui_draw.cpp, imgui_tables.cpp, imgui_widgets.cpp
	•	imgui_impl_dx11.cpp, imgui_impl_win32.cpp
	•	Include headers:
	•	imgui.h, imgui_internal.h, imgui_impl_dx11.h, imgui_impl_win32.h
	4.	Link DirectX 11 libraries
	•	d3d11.lib
	•	dxgi.lib
	•	d3dcompiler.lib
	•	(Set in Project Properties → Linker → Input → Additional Dependencies)
	5.	Set C++17 standard (Project Properties → C/C++ → Language → C++ Language Standard → ISO C++17).
	6.	Build the project.
	•	After a successful build, the executable will be in the project’s Debug or Release folder.
	7.	Run SkitzsAntiRecoil.exe
	•	The GUI will open.
	•	Adjust sliders, set hotkeys, and save configs as needed.

⸻

How to Use
	1.	Set Hotkeys
	•	Main Hotkey: Holds to activate mouse pulling.
	•	Toggle Hotkey: Turns the pulling on/off globally.
	•	Rapid Fire Hotkey: Toggles rapid-fire functionality.
	2.	Adjust Sliders
	•	Pull Down / Pull Right / Pull Left: Sets how much the mouse moves.
	•	Smoothness: Adjusts how smoothly the mouse moves.
	3.	Optional Features
	•	Required ADS: When enabled, pulling only works if both left + right buttons are pressed.
	•	Rapid Fire: Clicks repeatedly while the main hotkey is held down. Adjust speed with slider.
	4.	Configurations
	•	Save a configuration with a name.
	•	Load or delete existing configs via the dropdown.

⸻

Notes
	•	Designed for automation purposes only, not intended to cheat in any game.
	•	The program interacts directly with the mouse, so Windows may flag behavior if misused.
	•	Always test in a safe environment first.
	•	Config files are saved in the configs folder in the same directory as the executable.



i dont care if you use it in a game, but i dont take any responsablity if you get banned.
