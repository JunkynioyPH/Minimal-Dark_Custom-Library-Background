## ⚡ Minimal Dark for Steam ⚡ <br> 
Minimal Dark is a personalized and customizable minimal theme for the new Steam interface (New UI). <br>

Initially, it was a skin that I had made only for myself. <br>
After some thought I decided to share it with other people. <br>

I started from the basic Steam skin using the development tool (DevTools) as well as notepad++. <br>
All the sources and tools I used are at the bottom of the description. <br>

I'm not a coder or developer, I have notions and I do this on my free time when I have some. <br>
Be understandable if you encounter some bugs. <br>

That said, I hope you enjoy the interface! <br>
> this sharing is non-profit ! <br>

## `🎨 Customize theme with the color of your choice!🎨` <br> 

How change the skin color ? <br>
Open `-config.css-` with notepad++ and modify `line 4` and `line 6` ; save and reload Steam. <br> 

⚠️ note: color settings reset with each update (for now).<br>

`More simply` :<br>
- If you use the base color (which is Steam's default color, light blue): no problem since it is the base of the skin.<br>

`On the other hand` :<br>
- If you use a custom color: you will have to redefine the custom color during EACH update (for the moment) whether manual (by opening millenium from Steam settings) or automatic (when launching or restarting Steam).<br>

`Why ?` :<br>
- This is because Millennium, during an update reloads the entire Github directory and not just the updated files.<br>
I passed the information on to the dev, I'm waiting for his return (the problem does not occur with SFP).<br>

🗣️ Dev response : Millennium will be updated soon to resolve this issue to only update files changed during a skin update.


## `🧪 Restylised vanilla skin topbar + UI enhancements 🧪` <br> 

The home and collection button are now hidden to minimize the space taken up (they are accessible from the top bar). <br>

![minimal_dark](https://github.com/SaiyajinK/Minimal-Dark-for-Steam/assets/105972098/211949a5-8171-4ef8-9dac-ae56133bfbeb) <br>

![minimal_dark_1](https://github.com/SaiyajinK/Minimal-Dark-for-Steam/assets/105972098/5497af09-1460-4bd2-94c6-b7e8d2bc737b) <br>

I'm not a fan of heavy interfaces with "uncoordinated" colors. So I created a minimal topbar to best optimize the space compared to the vanilla base. <br> 

## `🔄 Reboot/recharge menu 🔄` <br> 

I added a js script to the skin that adds the restart and refresh UI actions. <br>
`Script has shared on the unofficial metro discord` <br>

![Reboot   recharge menu](https://github.com/SaiyajinK/Minimal-Dark-for-Steam/assets/105972098/7f73abce-ede6-4011-8053-305d197156b0) <br> 

## `📸 Compact mode + friends 📸` <br> 

![minimal_dark_2](https://github.com/SaiyajinK/Minimal-Dark-for-Steam/assets/105972098/a3577b4c-e5f9-4382-8433-b91751b4c92f) <br> 

## `🌐 Dark webkit 🌐` <br> 
`Thanks Shiina for the base of the webkit` <br>
I re-edited and fix the whole code according to my theme. <br>

![minimal_dark_w](https://github.com/SaiyajinK/Minimal-Dark-for-Steam/assets/105972098/907b1457-7b51-4fea-99b2-b1c8d1193e21) <br> 

## `✅ Quick installation with Millennium (recommanded) ✅` <br>
1️⃣ - Download & execute latest release of Millennium [here](https://millennium.web.app/)<br>
2️⃣ - Clic on  `Integrate` and wait for the end of integration (Steam will close)<br>
3️⃣ - Restart Steam and go `Settings` > `Interface` > `Steam Skin` > `Open Millennium`<br>
4️⃣ - In Millennium interface click on `Settings` and check that `JavaScript Execution` is checked.<br>
5️⃣ - Always in Millennium interface click on `Community` (Steam browser will open).<br>
6️⃣ - Select the Minimal Dark for Steam theme and drag `Drop onto Millennium button` in the Millennium and wait download & installation<br>
7️⃣ - Return to the `Library tab` and refresh the list of downloaded skins and click on `Minimal Dark for Steam`.<br>

## `🎥 Video installation 🎥`<br>
[<img src="https://i.imgur.com/ZjdSZPS.png" width="50%">](https://youtu.be/4GHb2_N6D3g)


## `🔗 Manual installation with SFP 🔗` <br>
1️⃣ - Download & extract latest release [here](https://github.com/SaiyajinK/Minimal-Dark-for-Steam/releases)<br>
2️⃣ - Copy `Minimal-Dark-for-Steam` folder to "C:\Program Files (x86)\Steam\steamui\skins\"<br>
3️⃣ - Download latest SFP [here](https://github.com/PhantomGamers/SFP/releases) <br>
4️⃣ - Launch SFP, in settings go to Steam, check "Inject JavaScript", and now select steam skin (steam will reload automatically). If you want dev Steam, type `-dev` on the end of launch arguments to get `-cef-enable-debugging -dev`.<br>

## `🛠️ Tools used 🛠️` <br>
- Steam DevTools <br>
- [Color picker](https://htmlcolorcodes.com/color-picker/) <br>
- [ColorSpace](https://mycolor.space) <br>
- [CSS Gradient](https://cssgradient.io/) <br>
- [Free SVG collection](https://thenounproject.com/) <br>

## `🖱️ Contributors links 🖱️` <br>
- [Shiina](https://github.com/AikoMidori/steam-dark-mode/blob/master/webkit.css) for the dark base of webkit<br>
- [Unofficial Patch for Metro for Steam](https://discord.gg/dMsSwufK7Q) for sharing reboot/reload script<br>
- [ShadowMonster99](https://github.com/ShadowMonster99/millennium-steam-patcher) for the implementation in Millennium<br>
