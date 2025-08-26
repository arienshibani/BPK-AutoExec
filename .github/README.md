# BPK Auto Exec

A high quality `autoexec` configuration chart for Counter-Strike 2 (CS2) with useful scripts, commands, and settings

- 🏎️ **Optimized values**
- 🛒 **Quickbuy binds, scripts and utility functions**
- 🛠️ **Easy to modify and maintain**
- 📜 **Documented commands**
- ✨ **Sane defaults**

## Installation guide

### 1. Download BPK AutoExec ⬇️
**[Download](https://github.com/arienshibani/BPK-AutoExec/archive/master.zip)** the latest version of the config. 

<img width="393" height="107" alt="image" src="https://github.com/user-attachments/assets/cf47ea61-a800-46a0-9d0d-d13bbc9fe867" />

### 2. Extract the files ⚙️ 
Open the _archive_ and **extract** the contents of the `cfg` folder into where your CS2 installation config folder exists. 
- That would typically be `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`

<img width="1717" height="469" alt="image" src="https://github.com/user-attachments/assets/e3243511-b909-4ec4-be07-17b1e06b12ab" />

### 3. Launch your new config 🚀
**Launch** the game and **type** in the _console_ the following command: `exec autoexec.cfg`


## Buy binds 🛒 

The BPK config comes with an easy to configure [template](https://github.com/arienshibani/BPK-AutoExec/blob/master/cfg/bpk/bind.cfg) for fast buys `bpk/binds.cfg`.

> Simply edit the binds.cfg file after installation to configure it to your own liking.

* Comes with a sane default with the following features.
  * Fetch all nades, armor + kit + main rifles instantly at round start. 
  * Suitable for TKL keyboards (does not rely on numpad).
  * Instantly sell everything with right-shift, for last minute eco round decisions.
```txt
                                                                                 
                                 Buy-binds                                       
             |-------------|-------------|-------------|--------------|          
             |      ins    |      home   |     pgup    |              |          
             |  Flashbang  |   HE-nade   |     Smoke   |  right-shift |          
             |-------------|-------------|-------------|              |          
             |      del    |     end     |     pgdn    |  sellbackall |          
             | kit + Armor |  AK47/M4A1s |   Molotov   |              |          
             |-------------|-------------|-------------|--------------|          
                                                                                 
```

### Util / Script binds ✨

* Utility binds and scripts
  * `F1`: Clutch mode (mute voicecomms)
  * `Q`: Enhanced quick swap (Hold down Q for knife, simply release to swap back to previous weapon.) 
  * `Capslock`: Insta drop C4
  * `Tab`: Show FPS and `net_graph`, but only when tab is held down.
  * Insta equip nades (no more nade cycling)
    * `mouse3`, `mouse4` and `mouse5` for insta equip HE, Flash and Smoke nades.
      * `x` for molotov + `c` for decoy. 


## More info
* If the autoexec isn't booting, perhaps try to use the launch option: `+exec autoexec.cfg`
    <img width="823" height="528" alt="image" src="https://github.com/user-attachments/assets/4b81a0d0-c77a-412b-ab5c-78d28930931c" />
* If you are met with ` [InputService] exec: couldn't exec '{*}cfg/autoexec.cfg'` messages in the console, double check that you extracted the `bpk`folder and the `autoexec.cfg` file into the correct folder.
* For a new desktop or operating system (e.g. Linux) make sure to put (again) in place all the files instead of letting the Steam cloud transfer them automatically.
* If you want to map your own keys to the binds in the config, follow the 
* Valve uses SDL scancodes for mapping keys. Use the reference image below to map your own keys.
  * <img width="640" height="172" alt="image" src="https://github.com/user-attachments/assets/ec538e46-5caa-436e-95a7-578bde2f3500" />

