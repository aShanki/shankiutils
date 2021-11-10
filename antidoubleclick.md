## 1. Disable Titlebar and Taskbar Previews when in Fullscreen Mode. (Windows Only)
This will show you, how to disable taskbar and titlebar previews when playing MCBE in fullscreen mode.
![image](https://user-images.githubusercontent.com/41850963/140021475-d045e817-165f-432c-9732-d6a2b49eb7d4.png)

1. Open `regedit`.

2. Navigate to this path: `HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`

3. It should look like this:     
![image](https://user-images.githubusercontent.com/41850963/140021433-5d5538a4-190e-4080-b805-e5305ab6d08f.png)

4. Add a new key with the name of `EdgeUI`:   
![image](https://user-images.githubusercontent.com/41850963/140021579-fbd44a7c-aada-462d-84d4-a1ac35352dbd.png)

5. Add a DWORD value with the name of `AllowEdgeSwipe`:           
![image](https://user-images.githubusercontent.com/41850963/140021687-10bfaff7-53a0-4235-a16d-fba09bbaf325.png)
