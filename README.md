# utils


### before we start

* **sl** steam locomotive
* **beep** npr `$ beep -r 2 -f 4000 -l 100`
* **man** manual. uporaba npr. `$ man man`

&nbsp;

### shell

* **zsh** z-shell zamenjava za bash, fish ...
* **oh-my-zsh** plugin za zsh (nujno) https://ohmyz.sh

&nbsp;

### c, compilers, debuggers

* **gcc** c compiler (all you need) https://gcc.gnu.org/
* **gcc-arm-none-eabi** gcc za arm
* **gcc-avr** gcc za avr
* **make** (nujno) rabis poleg gcc-ja https://www.gnu.org/software/make/
* **gdb** najboljsi debugger
* **radare2** unix-like reverse engineering framework and commandline tools https://github.com/radare/radare2
* **peda** reverse engineering plugin za gdb https://github.com/longld/peda
* **pwndbg** reverse engineering plugin za gdb 
* **python** zanimiv program v c-ju (vseeno pocasen) https://github.com/python/cpython
* **pdb** debugger za python
* **ldd** print shared object dependencies
* **strace** stack call trace
* **ltrace** library trace

&nbsp;

### 0xhex

* **hexedit** editiranje binary file-ov - tui
* **hexdump** hexdump utility
* **xxd** hexdump utility

&nbsp;

### programcki

* **tmux** tmux je novejsa (boljsa) alternativa za screen. 
* **screen** dela tudi npr `$ screen /dev/ttyUSB0` uporabne opcije: `-d -m -S` 
* **byobu** byobu je lepsi frontend za tmux in screen (ce mas tmux pol tega verjetno ne rabis)
* **dd** data destroyer. 
* **pv** pipe viewer
* **watch** konstantno refresha output neke komande
* **progress** pokaze trenutni status/napredek cp, mv, dd, tar...
* **xmodmap** za remap tipkovnice
* **xev**  prints content of X events (printa stevilke pritisnjenih tipk tipkovnice/miske)
* **uptime** up time
* **systemd-analyze** boot time `systemd-analyze blame`

&nbsp;

### vi

* **vi** originalni vi text editor 
* **vim** vi improved - boljsi text editor
* **nvim** neovim - zgleda isto kot vim sam je kao boljsi

&nbsp;

### ostali text editorji

* **sed** stream editor for filtering and transforming text
* **awk** gawk - pattern scanning and processing language
* **tr** translate or delete characters

&nbsp;

### internet...

* **arp-scan** ARP scanner (layer 2 - datalink layer)
* **netcat** tcp/ip scanner/tool $ nc ip port
* **wireshark** packate sniffer
* **iptables** firewall?
* **nmap** port scanner $ nmap -p- -sV -v 192.168..
* **traceroute** trace packets to network host
* **nmcli** command-line tool for controlling NetworkManager
* **nmtui** text-user-interface tool for controlling NetworkManager

&nbsp;

#### website
* **webhook.site** naredi webhook, https://webhook.site 
* **cyberchef** dekodiranje base64 in vec https://gchq.github.io/CyberChef/

&nbsp;

### audio, video

* **cmus** terminal music player
* **youtube-dl** downloadanje yt videov, playlistov... https://github.com/ytdl-org/youtube-dl/
* **ffmpeg** audio/video converter.. https://en.wikipedia.org/wiki/FFmpeg

&nbsp;

### file managment

* **find** najde datoteke in file-e. npr `sudo find / -xdev -name "*neki*"`
* **ranger** vi style file manager https://wiki.archlinux.org/index.php/Ranger
* **ssh** secure shell.. `-t, -N -L`
* **sshfs** mount ssh filesystem npr. `sshfs -o idmap=user -o ro tc@192.168.2.220:/server/path/ /local/path`
* **scp** secure copy
* **rsync** file copying tool `-v, -a, -n, --delete, -H`
* **fdupes** najde duplikate file-ov v doloceni mapi (lahko jih tudi zbrise)
* **tree** narise drevo
* **tar** compress: `-zcvf` extract: `-zxvf`
* **git** boljsi kot subversion
* **ncdu** zelo lep prikaz velikosti file-ov (tui)
* **id3v2** music metadata tag editor (and viewer)

&nbsp;

### emulacija

* **qemu** emulator/vm
* **qemu-kvm** emulator/vm

&nbsp;&nbsp;&nbsp;&nbsp;

## non command line - gui:

* **kicad** pcb design
* **InteractiveHtmlBom** naredi interaktivni BOM iz kicad pcb-ja (cli)
* **freecad** parametricni 3d modelirnik

&nbsp;

* **sigrok pulseview** gui logic analyzer software (dela tudi z DS1054Z) (obstaja tudi command-line verzija sigrok-cli)

&nbsp;

* **pychart** kao excel sam da v celice pises python kodo

&nbsp;

* **krdc** kde remote desktop client za vnc in rdp
* **tigerVNC** remote desktop client VNC

