# About the Project

*UniVenture* was developed as a first year group final project in Universidad Nacional De San Martín.
The purpose of developing this game in Assembly was to fully understand the usage of stack memory and processor interrupts.
In this case, we are using TASM to emulate the Intel 8086 micro-chip.

# Preview

<img src="https://i.postimg.cc/3Jv0YZnX/1.png" width="800" />
<img src="https://i.postimg.cc/K8hkzgHd/2.png" width="800" />
<img src="https://i.postimg.cc/g2yw629r/3.png" width="800" />

# Installation

- [*Click here*](https://drive.google.com/file/d/1x6kMkZ87AYE8qTNe7m3SXRMuJPv6f3QS/view?usp=sharing) to access the directory
- Download the *rar* file
- Extract the content in a folder
- Install *Tasm-1.4-Techapple.net.exe* from *emulator* folder
- Copy *DEBUG.EXE* and paste it in *C:\Tasm 1.4\Tasm*
- Copy *storyxs.asm* and *add.asm* from *game* folder
- Paste both files in *C:\Tasm 1.4\Tasm*
- Run *DOSBox.exe*
- Type the following commands in order, pressing enter at the end of every line:
```
tasm storyxs
tasm add
tlink storyxs
tlink add
storyxs
```

# Authors

- [Cristian Villafañez](https://github.com/KZvilla)
- [Valentino Bortolussi](https://github.com/Valentino-afk)
- [Diego Alegre](https://github.com/PipoJR10)
- Matías Di Stefano
- [Martín De Lojo](https://www.github.com/martinmdl)
