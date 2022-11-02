# About 'vulner'

<p align="center">
   </a>
      <a href="https://github.com/gh0st-anonymous/analyzer">
      <img src="https://img.shields.io/badge/Version-1.0.0-darkgreen">
        <img src="https://img.shields.io/badge/Release%20Date-june%202022-purple">
  <img src="https://shields.io/badge/Bash-100%25-066da5">
  <img src="https://shields.io/badge/Platform-Linux-darkred">
    </a>
  </p>
</p>

vulner is a bash script that maps network devices for ports, services and will look after vulnerabilities to exploit using:

[nmap](https://www.kali.org/tools/nmap/), [masscan](https://www.kali.org/tools/masscan/), [hydra](https://www.kali.org/tools/hydra/), [searchsploit](https://www.kali.org/tools/exploitdb/) and [msfconsole](https://www.kali.org/tools/metasploit-framework/).

### Possibility and Capability

> ADVANTAGES:

- will save the user general scans in a statistics file.

- check if the new supposed output file or directory is already created. (instead of :: error cant write on 'file.txt' because 'file.txt' already exist :: you'll get file.2.txt or dir.2 then .3, .4, ect...)

- check for every errors possible. (correct answers as input, if the VPN is truly active or if he failed)

- the required dependencies and libraries will be scanned and any missing packages will be installed automatically.

- use -i for info for the script resume, type [sudo] bash  / ./vulner -i

- use -h for help for the script usage, type [sudo] bash  / ./vulner -h

- help and info menu doesn't require sudo privileges.

> DISADVANTAGES:

- none.


### 'vulner' Project

a [project](https://github.com/gh0st-anonymous/vulner/files/9901643/project.pdf) made by [ThinkCyber](https://www.thinkcyber.co.il/).


### Video Demonstration

Be Aware: the script could be different from the video since he got upgraded.

[![image](https://user-images.githubusercontent.com/102325071/199022744-b17d079f-6cc6-45f6-ba1e-95d3e0c82f54.jpg)
](https://www.youtube.com/watch?v=Ghh3wMwek1M)

### Script Usage

launch the script by typing:

![pic](https://user-images.githubusercontent.com/102325071/199060618-7016f941-0c28-4aa2-a62e-c07a0d653d37.png)

-h (stand for help) for more info about the flags options.

-i (stand for info) for more info about the script.

### Download

from [zip](https://github.com/gh0st-anonymous/remote-control/files/9900001/remote.control.zip) file or from github: 

    git clone https://github.com/gh0st-anonymous/vulner
