<br/>

[banner](https://github.com/WiseManGNU/Windhawk_Win11AmoledTheme/blob/main/assets/banner.png?raw=true)

<p align="center">
A simple and short guide on how to make most of the UWP Desktop UI solid-black with Windhawk.
</p>

<br/>
<br/>

# Requirements / Prerequisites
|Mod|Author|Version Used|
|---|------|------------|
|[Windhawk Application](https://windhawk.net/)|Ramen Software|v1.5.1|
|[Taskbar Styler](https://windhawk.net/mods/windows-11-taskbar-styler)|m417z|v1.3.10|
|[Start Menu Styler](https://windhawk.net/mods/windows-11-start-menu-styler)|m417z|v1.2.1|
|[Notification Center Styler](https://windhawk.net/mods/windows-11-notification-center-styler)|m417z|v1.1.6|
<br/>

# Taskbar and System Tray
In **Windhawk**, find the **Taskbar Styler** mod, click **Details > Advanced** and add the following below to your **mod settings**, then click save.

```json
{"theme":"","controlStyles[0].target":"Taskbar.TaskbarFrame > Grid#RootGrid > Taskbar.TaskbarBackground > Grid > Rectangle#BackgroundFill","controlStyles[0].styles[0]":"Fill=Black","resourceVariables[0].variableKey":"","resourceVariables[0].value":"","controlStyles[1].target":"Rectangle#BackgroundStroke","controlStyles[1].styles[0]":"Fill=Black","controlStyles[2].target":"Grid#OverflowRootGrid > Border","controlStyles[2].styles[0]":"Background=Black"}
```

<br>
<br/>

# Start Menu and Search-Box
In **Windhawk**, find the **Start Menu Styler** mod, click **Details > Advanced** and add the following below to your **mod settings**, then click save.

```json
{"theme":"","webContentCustomJs":"","resourceVariables[0].variableKey":"","resourceVariables[0].value":"","controlStyles[0].target":"Windows.UI.Xaml.Controls.Border#AcrylicBorder","controlStyles[0].styles[0]":"Background=Black","controlStyles[1].target":"Windows.UI.Xaml.Controls.Border#AcrylicOverlay","controlStyles[1].styles[0]":"Opacity=0","controlStyles[2].target":"Windows.UI.Xaml.Controls.Grid#TopLevelRoot > Windows.UI.Xaml.Controls.Border","controlStyles[2].styles[0]":"Background=Black","controlStyles[1].styles[1]":"","controlStyles[3].target":"Windows.UI.Xaml.Controls.Border#TaskbarSearchBackground","controlStyles[3].styles[0]":"Background=Black","controlStyles[4].target":"Windows.UI.Xaml.Controls.Border#AcrylicBorder","controlStyles[4].styles[0]":"BorderBrush=Black","controlStyles[5].target":"Windows.UI.Xaml.Controls.Border#AppBorder","controlStyles[5].styles[0]":"Background=Black","controlStyles[6].target":"Windows.UI.Xaml.Controls.Border#LayerBorder","controlStyles[6].styles[0]":"Opacity=0","controlStyles[7].target":"Border#AppBorder","controlStyles[7].styles[0]":"BorderThickness=0"}
```

<br>
<br/>

# Notification Center and Action Center
In **Windhawk**, find the **Notification Center Styler** mod, click **Details > Advanced** and add the following below to your **mod settings**, then click save.

```json
{"theme":"","controlStyles[0].target":"Grid#NotificationCenterGrid","controlStyles[0].styles[0]":"BorderThickness=0,0,0,0","controlStyles[0].styles[1]":"Background=Black","controlStyles[1].target":"Grid#CalendarCenterGrid","controlStyles[1].styles[0]":"BorderThickness=0,0,0,0","controlStyles[1].styles[1]":"Background=Black","controlStyles[2].target":"ScrollViewer#CalendarControlScrollViewer","controlStyles[2].styles[0]":"Background=Black","controlStyles[3].target":"ActionCenter.FocusSessionControl#FocusSessionControl > Grid#FocusGrid","controlStyles[3].styles[0]":"Background=Black","controlStyles[4].target":"Border#CalendarHeaderMinimizedOverlay","controlStyles[4].styles[0]":"Background=Black","controlStyles[5].target":"Windows.UI.Xaml.Controls.Grid#MediaTransportControlsRegion","controlStyles[5].styles[0]":"Background=Black","controlStyles[6].target":"Grid#MediaTransportControlsRoot","controlStyles[6].styles[0]":"Background=Black","controlStyles[7].target":"Windows.UI.Xaml.Controls.Grid#MediaTransportControlsRegion","controlStyles[7].styles[0]":"BorderThickness=0,0,0,0","controlStyles[8].target":"Grid#ControlCenterRegion","controlStyles[8].styles[0]":"BorderThickness=0,0,0,0","controlStyles[8].styles[1]":"Background=Black","controlStyles[9].target":"Windows.UI.Xaml.Controls.Grid#L1Grid > Border","controlStyles[9].styles[0]":"Background=Black","controlStyles[10].target":"Border#JumpListRestyledAcrylic","controlStyles[10].styles[0]":"Background=Black","controlStyles[10].styles[1]":"BorderThickness=0,0,0,0"}
```

<br>
<br/>
