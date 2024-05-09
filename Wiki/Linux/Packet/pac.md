## [Назад](../lin.md)

### <center>Менеджер пакетов ✔️</center>
`- набор программного обеспечения, позволяющего управлять процессом установки, удаления, настройки и обновления различных компонентов программного обеспечения. Системы управления пакетами активно используются в различных дистрибутивах операционной системы Linux и других UNIX-подобных операционных системах.`

Программное обеспечение представляется в виде особых пакетов, содержащих, помимо дистрибутива программного обеспечения, набор определённых метаданных, которые могут включать в себя полное имя пакета, номер версии, описание пакета, имя разработчика, контрольную сумму, отношения с другими пакетами. Метаданные сохраняются в системной базе данных пакетов.

#### Существует множество систем управления пакетами, вот некоторые из них:

- <b>RPM и yum</b> (система управления пакетами Red Hat, использующаяся во множестве дистрибутивов Linux, в том числе Fedora, RHEL, ASP Linux, Mandriva, OpenMandriva Lx, openSUSE)
- <b>dpkg и apt</b> (система управления пакетами в Debian и в различных дистрибутивах, основанных на нём, например Ubuntu),
- <b>Pacman</b> (менеджер пакетов в Arch-подобных дистрибутивах),
- <b>Portage</b> (основная система управления пакетами в Gentoo, аналог системы портов FreeBSD),
- <b>Entropy</b> (система управления пакетами в Sabayon Linux),
- <b>PiSi</b> (система управления пакетами, используется турецким дистрибутивом Pardus),
- <b>Image Packaging System</b> (система управления пакетами для OpenSolaris)


#### Иерархия пакетных менеджеров ✔️

- Debian (apt, dpkg) ⚜️
    - Ubuntu (apt, dpkg)
        - Linux Mint (apt, dpkg)
        - Elementary OS (apt, dpkg)
    - Knoppix (apt, dpkg)
    - Kali Linux (apt, dpkg)
- Red Hat (yum/dnf, rpm) ⚜️
    - Fedora (dnf, rpm)
        - CentOS (yum/dnf, rpm)
    - Mandrake (urpmi, rpm)
        - Mandriva (urpmi, rpm)
            - Mageia (dnf, rpm)
    - Rocky Linux (yum/dnf, rpm)
- Slackware (pkgtools, rpm) ⚜️
    - SUSE Linux (zypper, rpm)
        - openSUSE (zypper, rpm)
            - SUSE Linux Enterprise Server/Desktop (zypper, rpm)
    - Slacko Puppy Linux (pkgtool, rpm)
- Arch Linux (pacman) ⚜️
    - Manjaro (pacman)
- Alt Linux (apt/yum, rpm)

