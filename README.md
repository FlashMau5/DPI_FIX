# DPI-Fix
Simple method to fix blurry programs on Windows with few clicks.

<details><summary>Download</summary>
<p>

Just click on "Code▾" then "Download ZIP" or [Here](https://github.com/FlashMau5/DPI_FIX/archive/refs/heads/main.zip)  
  
![Download](https://user-images.githubusercontent.com/33010589/155316777-06a476df-77f3-4229-b74b-a3e590ae51b5.png)

</p>
</details>

<details><summary>Installation</summary>
<p>

Just open the [INSTALLER].reg file then click Yes and OK  
  
![Install1](https://user-images.githubusercontent.com/33010589/155311400-d2868db7-5ccf-404a-8b82-f713ed0ee38c.png)  
![Install2](https://user-images.githubusercontent.com/33010589/155311414-782bafbe-0238-4d4c-ac6c-a0fe4840eb8d.png)  
![Install3](https://user-images.githubusercontent.com/33010589/155311423-a4e81fcf-1a0a-446e-96a8-054beac54297.png)

</p>
</details>

<details><summary>Uninstallation</summary>
<p>

Just open the [UNINSTALLER].reg file then click Yes and OK  
  
![Uninstall1](https://user-images.githubusercontent.com/33010589/155312010-c89a4fef-9096-4b42-a13b-47e7c4753ba2.png)  
![Uninstall2](https://user-images.githubusercontent.com/33010589/155312162-8464c156-68c3-4dad-888f-25912d5f8445.png)  
![Uninstall3](https://user-images.githubusercontent.com/33010589/155312168-1f7c6b57-67d0-4d7d-a073-971507c0ab47.png)
</p>
</details>

<details><summary>Usage</summary>
<p>

- Right click on blurry exe file or its shortcut and choose the method to use with left click. (Usually Standard works well)  
- Choose "None" to disable the Fix
  
![Usage](https://user-images.githubusercontent.com/33010589/155312341-588f0c7f-0788-4fd1-ba6b-d27e77a2ccc2.png)

</p>
</details>

<details><summary>Methods and How it works</summary>
<p>

#### Methods
- Standard set the exe in Windows Registry as: "~ PERPROCESSSYSTEMDPIFORCEOFF HIGHDPIAWARE"
- Alternative 1 set the exe in Windows Registry as: "~ PERPROCESSSYSTEMDPIFORCEOFF DPIUNAWARE"
- Alternative 2 set the exe in Windows Registry as: "~ PERPROCESSSYSTEMDPIFORCEOFF GDIDPISCALING DPIUNAWARE"
- All "as Admin" set the method + "RUNASADMIN"

#### How it works
- DPI-Fix by FlashMau5 is a shell shortcut (It shows when you right click on an EXE file)  
- All the methods change the DPI proprieties of the exe in Windows Registry in this path: "Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\Layers"  
- Previous compatibility settings will be overwritten  
  
![Working](https://user-images.githubusercontent.com/33010589/155315703-47dd74e9-8202-4937-8f0b-6057a698c63e.png)


</p>
</details>
