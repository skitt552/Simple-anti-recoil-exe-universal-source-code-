Mouse Puller – README

Overview

This program allows controlled mouse movement with customizable sliders for down, left, right, and smoothness, along with rapid-fire functionality, named configs, and a Required ADS toggle. Built with C++, DirectX 11, and ImGui for the interface.

⚠️ Warning: Programs that simulate mouse/keyboard input may be flagged by Windows Defender as potentially unwanted software. Use responsibly.

⸻

Features
	•	Mouse Pulling:
	•	Pull down, left, or right.
	•	Smoothness adjustment.
	•	Toggle on/off with hotkey.
	•	Executes while main hotkey is held.
	•	Rapid Fire:
	•	Toggle on/off with a hotkey.
	•	Only activates while main hotkey is held.
	•	Adjustable speed (ms between clicks).
	•	Config System:
	•	Save/load named configs.
	•	Delete configs.
	•	Configs stored in configs/ folder.
	•	Required ADS:
	•	Mouse pulling only works if both Left + Right mouse buttons are held.
	•	Adjustable delay (50–200ms) for checking button press.
	•	Hotkey Remapping:
	•	Main hotkey
	•	Toggle hotkey
	•	Rapid-fire toggle hotkey
	•	GUI:
	•	Pink and black themed menu using ImGui.

⸻

Requirements

Software
	1.	Windows 10 or 11
	2.	Visual Studio 2022 (or 2019 with C++ support)
	3.	DirectX 11 SDK (usually included in Windows SDK)
	4.	ImGui library
	•	imgui.h, imgui.cpp, imgui_impl_win32.cpp, imgui_impl_dx11.cpp (and corresponding headers)
	•	Can be downloaded from https://github.com/ocornut/imgui
	5.	C++17 or later compiler support

Hardware
	•	Any standard Windows PC with mouse input support.

⸻

Setup Instructions
	1.	Clone / copy the project into a Visual Studio solution.
	2.	Include ImGui in your project and link the files:
	•	imgui.cpp, imgui_draw.cpp, imgui_widgets.cpp, imgui_tables.cpp
	•	Platform/renderer files: imgui_impl_win32.cpp, imgui_impl_dx11.cpp
	3.	Add DirectX 11 libraries to linker settings:
	•	d3d11.lib, dxgi.lib, d3dcompiler.lib
	4.	Create a folder called configs in the same directory as the compiled EXE.
	5.	Compile in Release or Debug mode.

⸻

Usage
	1.	Run the compiled EXE.
	2.	Use the sliders to adjust pulling down/left/right and smoothness.
	3.	Set or use default hotkeys:
	•	Main hotkey: hold to pull mouse.
	•	Toggle hotkey: toggle mouse pulling on/off.
	•	Rapid-fire hotkey: toggle rapid-fire on/off.
	4.	Save/load named configs for quick switching.
	5.	Enable Required ADS if you want pulling to only work while Left + Right buttons are pressed.
	6.	Adjust rapid-fire speed to control click frequency.

⸻

Notes
	•	Windows Defender may flag the EXE as potentially unwanted due to simulated mouse input.
	•	Always use responsibly; do not use in environments where automation is prohibited.
	•	The program must be run in desktop mode; does not work in UWP sandboxed apps.
	•	Configs are stored in binary format inside the configs folder.
