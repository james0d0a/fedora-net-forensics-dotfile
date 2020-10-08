# fedora-net-forensics-dotfile

This repo uses YADM to manage dot files for my fedora based network forensics box.

# install
* install yadm via DNF
`
dnf config-manager --add-repo https://download.opensuse.org/repositories/home:TheLocehiliosan:yadm/Fedora_Rawhide/home:TheLocehiliosan:yadm.repo
dnf install yadm
`
* clone and bootstrap via yadm
`yadm clone --bootstrap https://github.com/james0d0a/fedora-net-forensics-dotfile.git`
