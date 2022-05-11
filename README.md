# SDL_WINDOWID
Global $iBlittingMethod = 1, $asBlittingMethod[4] = ["", "SDL", "GDI+", "GDI+wSDL"] HotKeySet("{SPACE}", "_Next") Local $iWidth = 800, $iHeight = 600 $hGui = GUICreate(StringTrimRight(@ScriptName, 4), $iWidth, $iHeight, 0, 0) EnvSet("SDL_WINDOWID", $hGui) _SDL_Init($_SDL_INIT_VIDEO)
