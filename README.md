__original github:__  
https://github.com/GhostDuckyy/UI-Libraries/tree/main/Vape%20ui%20lib  

### example loadstring
```lua
-- this is the example script, if you wanna check the example source code, just check it out, only did this because i was lazy ngl.
loadstring(game:HttpGet("https://raw.githubusercontent.com/nonfq/Vape-UiLibrary/main/example.luau"))()
```

## updates

> 10/13/26  
[+] Tab list scrolls: with many tabs on a small UI, extra tabs no longer get cut off (touch drag on mobile, mouse wheel on PC)  
[+] Tab side and menu side are now two separate panels, each with its own drag bar so you can move them independently  
[+] The panel you grab comes to the front, so they can overlap either way round  
[+] Tab panel auto-sizes to its tabs: short for a few tabs, taller for many, up to screen height, then it scrolls  
[+] Minimize keeps the title bars in place instead of jumping to the middle  
[+] Mobile toggle button is now a capsule (78x32) labeled "MENU"  
[+] Section labels sit 1.4px higher  
[-] Single combined window (tab side and menu side were locked together)  
[-] Fixed tab list height that hid tabs past the window size  
[-] Round mobile button with the single-letter label  
[-] Section text size 13 (now 12)   

> 10/02/2026  
[+] rounded the window and elements slightly.  
[+] added Light, Dark and Black themes, with a smooth fade when switching.  
[+] added `lib:SetTheme(name)` and `lib:GetTheme()`.  
[+] added theme dropdown to the Settings tab.  
[+] added `theme` option to `lib:Window`.  
[+] added smooth animations: window fade in/out, tab content slide.  
[+] added Updates tab to the example script.  
[+] colorpicker now defaults to white.  
[+] "Change UI Color" now defaults to white, and switches to black when the theme is Light.  
[+] added `:Set(color)` to colorpickers, to set them from code.  
[+] fixed colorpicker selectors starting in the wrong position.  
[+] toggle knob now turns dark when the accent color is very light.  
[-] removed the demo Colorpicker from the example script.  
[+] redesigned dropdown options as rounded buttons with a hover effect, and an accent bar and check on the picked option.  
[+] added window transparency option, elements follow at window + 0.25.  
[+] added window size option (Vector2).  
[+] redesigned Label to look like plain text instead of a button.  
[+] moved Section headers higher.  
[+] simplified the example script comments.  
[+] fixed colorpicker box and textbox field position on custom window sizes.  
[+] close and minimize buttons now fade in on hover when the window is transparent.  

> 07/18/2026  
[+] added support lucide icons for button, toggle.  

> 07/17/2026  
[+] added lucide icons.   
[-] removed Movement tab.  
[+] added paragraphs, with avatar.  
[+] added drag to the mobile close/open button.  

> 07/16/2026  
[+] added setting tab, with change theme, fully close ui.  
[-] removed change theme tab.  
[+] added section code.  
[+] added movement tab.  
[+] updated the example script.  

> 07/15/2026  
[+] fixed color picker not working for mobile.  
[+] fixed slider.  
[+] added minimize button, close button.  
[+] added a button for mobile users only to hide/show the ui.
