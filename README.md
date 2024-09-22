## Modified version to allow for Custom Backgrounds to be used in the Library Page
# Minimal_Dark_for_steam-v3.3.1
Because we want something simple yet a nice background.
Just modify the JunkyModifications.css to change the background. <br>

![minimal](https://cdn.discordapp.com/attachments/894153595367329816/1287223698750832640/image.png?ex=66f0c3fd&is=66ef727d&hm=b14d3f6885616bdf31574a4308ff59301a03924dfad53d567a9e76006bf35ca9&) <br>

### ---- ORIGINAL README FROM AUTHOR ----
[![KoFi](https://i.imgur.com/VnXqmO2.png)](https://ko-fi.com/saiyajink)

## ⚡ Minimal Dark for Steam ⚡ <br> 

Minimal Dark is a personalized and customizable minimal theme for the new Steam interface (New UI). <br>
I started from the basic Steam skin using the development tool (DevTools) as well as notepad++. <br>
All the sources and tools I used are at the bottom of the description. <br>

I am neither a coder nor a developer, I have some knowledge after several years of practice and I do this in my free time when I have it. <br>
Be understanding if you encounter any bugs. <br>

## `🧪 Restylised vanilla skin topbar + UI enhancements 🧪` <br> 

![minimal](https://github.com/user-attachments/assets/02eebc2e-fbd8-48fa-9c4e-f2f05b434d9b) <br>

I created a minimal topbar to best optimize the space compared to the vanilla base. <br>
The home and collection button are now hidden to minimize the space taken up (they are accessible from the top bar). <br>

## `🎨 Customize theme with the color of your choice 🎨` <br> 

I'm not a fan of heavy interfaces with "uncoordinated" colors. So I did my best to have a theme with matching colorimetry. In building the skin, I defined a function on many elements that injects the color code defined in the configuration file across the entire skin and webkit. <br>

How change the skin color ? <br>
1. Open `config.css` with notepad++ and modify lines `4` and `5`. <br> 
2. Open `webkit.css` and modify lines `8` and `9` ; save and reload Steam. <br> 

⚠️ note: color settings reset with each update (for now).<br>

More simply : If you use the base color (which is Steam's default color, light blue): no problem since it is the base of the skin.<br>

On the other hand : If you use a custom color: you will have to redefine the custom color during EACH update (for the moment) whether manual (by opening millenium from Steam settings) or automatic (when launching or restarting Steam).<br>

Why ? : This is because Millennium, during an update reloads the entire Github directory and not just the updated files.<br>
I passed the information on to the dev, I'm waiting for his return (the problem does not occur with SFP).<br>

🗣️ Dev response : Millennium will be updated soon to resolve this issue to only update files changed during a skin update.

## `📸 Compact mode + friends 📸` <br> 

![minimal__](https://github.com/user-attachments/assets/a3328862-364b-4da2-aca0-d7dbc31e876a) <br>

## `👤 Profil 👤` <br> 

Some profiles have neon lights around the headers, I removed them by default.<br>
If you want to remove this, open `webkit.css` and remove line `100`<br>

![minimal_](https://github.com/user-attachments/assets/8569c004-6afe-4037-8fac-044480b631a4) <br>

## `🌐 Dark webkit 🌐` <br> 
`Thanks Shiina for the base of the webkit` <br>
All aspects were changed to match my theme. <br>

![minimal___](https://github.com/user-attachments/assets/5c66213e-8a71-4a2d-94ad-8e0223509572) <br>

## `✅ Quick installation with Millennium (recommanded) ✅` <br>
1️⃣ - Download & execute latest release of Millennium [here](https://millennium.web.app/)<br>
2️⃣ - Clic on  `Integrate` and wait for the end of integration (Steam will close)<br>
3️⃣ - Restart Steam and go `Settings` > `Interface` > `Steam Skin` > `Open Millennium`<br>
4️⃣ - In Millennium interface click on `Settings` and check that `JavaScript Execution` is checked.<br>
5️⃣ - Always in Millennium interface click on `Community` (Steam browser will open).<br>
6️⃣ - Select the Minimal Dark for Steam theme and drag `Drop onto Millennium button` in the Millennium and wait download & installation<br>
7️⃣ - Return to the `Library tab` and refresh the list of downloaded skins and click on `Minimal Dark for Steam`.<br>

> Installation documentation : https://millennium.gitbook.io/steam-patcher/getting-started/installation <br>

## `🔗 Manual installation with SFP 🔗` <br>
1️⃣ - Download & extract latest release [here](https://github.com/SaiyajinK/Minimal-Dark-for-Steam/releases)<br>
2️⃣ - Copy `Minimal-Dark-for-Steam` folder to "C:\Program Files (x86)\Steam\steamui\skins\"<br>
3️⃣ - Download the latest SFP version [here](https://github.com/PhantomGamers/SFP/releases) <br>
4️⃣ - Launch SFP, in settings go to Steam, check "Inject JavaScript", and now select steam skin (steam will reload automatically). If you want dev Steam, type `-dev` on the end of launch arguments to get `-cef-enable-debugging -dev`.<br>

## `🛠️ Tools used 🛠️` <br>
- Steam DevTools <br>
- [Color picker](https://htmlcolorcodes.com/color-picker/) <br>
- [ColorSpace](https://mycolor.space) <br>
- [CSS Gradient](https://cssgradient.io/) <br>
- [Free SVG collection](https://thenounproject.com/) <br>

## `🖱️ Open Source References 🖱️` <br>
- Credits to [Rose's Metro for Steam](https://github.com/RoseTheFlower) for the initial base of the theme and the inspiration it gave me.
- [Shiina](https://github.com/AikoMidori/steam-dark-mode/blob/master/webkit.css) for the dark base of webkit<br>
- [Unofficial Patch for Metro for Steam](https://discord.gg/dMsSwufK7Q) for sharing reboot/reload script<br>
- [ShadowMonster99](https://github.com/ShadowMonster99/millennium-steam-patcher) for the implementation in Millennium<br>
- [PhantomGamers](https://github.com/PhantomGamers) for SFP and the reboot/reload script <br>
- [LaserFlash](https://github.com/LaserFlash) for WaitForElement module <br>
- [Icon8](https://icons8.com) for Base64 icons

------

[![KoFi](https://i.imgur.com/VnXqmO2.png)](https://ko-fi.com/saiyajink)
