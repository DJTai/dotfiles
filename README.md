# dotfiles

### **Don't reinvent the wheel**.

My overall theme was jumpstarted from unix121's [i3wm-themer](https://github.com/unix121/i3wm-themer). The steps to utilize this wonderful tool can be found [here](https://github.com/unix121/i3wm-themer#using-the-script).

## My Specs
- **OS:** [Manjaro](https://manjaro.org/)
- **WM:** i3[\*](https://manjaro.org/download/community/i3/)
- **Shell:** [bash](https://www.gnu.org/software/bash/)
- **Terminal:** urxvt
- **Status Bar:** [polybar](https://github.com/polybar/polybar)
- **App launcher:** [rofi](https://github.com/davatorium/rofi)

**NOTE**: Copy + paste *at your own risk*. I recommend that you use my files as a reference, i.e., don't just replace your file with mine. Please backup your files before you attempt to change anything on your computer.



### dotfiles?
I assume you know what dotfiles are, but if you don't then that's okay. Basically, dotfiles are text-based configuration files, i.e., they store the settings of your applications.



### Where are these files located?
*everywhere...* but seriously, they are generally found (at least in my experience) in the typical locations on a UNIX-type system.
- All of the files and folders that begin with a `.` are typically found in your home direcory. For example, if your username on your computer is `XYZ`, then you would find `.config` at:
    - `/home/XYZ/.config` or simply `~/.config`
- The `etc` folder and `usr` folder are found at `/`, i.e., `/etc` and `/usr`



### Why would you post these online?
1. For backup reasons (in case I screw something up while messing around with my dotfiles)
2. For portability reasons (in case I have another computer that I want the same configuration on)
3. For sharing reasons
