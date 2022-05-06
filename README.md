# Th3m3 H0sp1t4l *DOSBox*

## Installation

- Define a **game directory path**. For example:
  - `c:\Users\username\Theme-Hospital` on Windows
  - `/home/username/Theme-Hospital` on <var>*</var>Nix (macOS, GNU/Linux, <span lang="lt">et cetera</span>)
- Go to game directory: <code><kbd>cd <var>game directory</var></kbd></code>
- ⬇️ Download the game `git clone https://github.com/m4l4v1t4/Th3m3-H0sp1t4l-DOSBox.git`


## Running the game ⏯️

<code><kbd>dosbox -conf "<var>game directory path<var>/</var></var>dosboxTH.conf" "<var>game directory path<var>/</var></var>HOSPITAL.EXE"</kbd></code>

For example:
- (**on linux** OS): `dosbox -conf ~/theme-hospital/dosboxTH.conf ~/theme-hospital/HOSPITAL.EXE`
- Or, `dosbox -conf "c:\Users\username\theme-hospital\dosboxTH.conf" "c:\Users\username\theme-hospital\HOSPITAL.EXE` **on Windows** OS.

### Linux launcher

- Copy `./theme-hospital-dosbox.desktop` to launcher applications directory of the distro (<code><kbd>/home/<var>username</var>/.local/share/applications/</kbd></code> on Debian like's ditros). ⚠️ The lancher file needs to be personalized with the path to the game directory