# 🧠 SimCity 2013 – OptionScreenSize Resolution Map

SimCity 2013 uses an internal parameter called `OptionScreenSize` to select screen resolution. This value is not a direct resolution like "1920x1080", but an index pointing to a predefined resolution and refresh rate combination.

Thanks to reverse engineering, here is a partial map of known values:

## 📊 Resolution Table

| OptionScreenSize | Resolution     | Refresh Rate |
|------------------|----------------|--------------|
| 1                | 1024×768       | 100 Hz       |
| 3                | 1024×768       | 60 Hz        |
| 5                | 1024×768       | 165 Hz       |
| 6                | 1024×768       | 144 Hz       |
| 7                | 1024×768       | 70 Hz        |
| 8                | 1152×864       | 120 Hz       |
| 9                | 1152×864       | 100 Hz       |
| 15               | 1280×720       | 60 Hz        |
| 18               | 1280×720       | 120 Hz       |
| 30               | 1280×768       | 144 Hz       |
| 35               | 1280×800       | 119 Hz       |
| 40               | 1280×960       | 75 Hz        |
| 41               | 1280×960       | 60 Hz        |
| 50               | 1280×1024      | 165 Hz       |
| 64               | 1366×768       | 120 Hz       |
| 100              | 1680×1050      | 120 Hz       |
| 109              | 1920×1080      | 120 Hz       |
| 110              | 1920×1080      | 100 Hz       |
| 111              | 1920×1080      | 75 Hz        |
| 112              | 1920×1080      | 119 Hz       |
| 113              | 1920×1080      | 165 Hz       |

---

## 🛠️ How to Force Resolution

To force SimCity to launch in a specific resolution, edit the preferences file and set:

```txt
OptionScreenSize 110
OptionFullScreen 1
OptionFitToScreen 1
OptionNoWindowBorders 0

✅ This will launch the game in fullscreen 1920×1080 at 100 Hz.

##📁 File Location (EA App version)

The preferences file is located at:

C:\Users\<your-username>\AppData\Roaming\SimCity\Preferences

Replace <your-username> with your actual Windows account name.

##💡 Contribute

Found more values? Help expand the table! Share your findings with:

OptionScreenSize value

Resolution and refresh rate

GPU and monitor used

This helps modern users unlock full graphics potential in SimCity 2013.

