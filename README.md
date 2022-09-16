
## CentOS Stream 9 || Debian 11 Bullseye
    
- swapfile...efi.../.boot.usr.var.home.tmp ` # /etc/sysctl.conf @vm.swappiness=60 `
 - bin-dev-lib-libx32-mnt-root-snap-sys 
 - etc-lib32-lost+found-opt-run-srv 
 - cdrom-lib64-media-proc-sbin  
---
## Linux Browser Google Chrome && Chromium

~~[`webcrawler`](https://www.webcrawler.com/)~~
 [` @musicenc `](https://www.musicenc.com/)
 [` @yandex `](https://yandex.com/)
 [` @kernel.ubuntu `](https://kernel.ubuntu.com/~kernel-ppa/mainline/)
 [` @wolframalpha `](https://www.wolframalpha.com/)
 [` @git-scm `](https://git-scm.com/)
 [` @cdn-linux-kernal `](https://cdn.kernel.org/pub/linux/kernel/v5.x/)
 
 [` @md5hashing `](https://md5hashing.net/)
 [` @md5calc `](https://md5calc.com/)
 [` @freedesktop `](https://people.freedesktop.org/)
 [` @ventoy `](https://www.ventoy.net/en/index.html) ` # New Bootable USB Solution `
 [` @cdimage-debian `](https://cdimage.debian.org/images/) ` # debian release || unofficial `
 [` @gstreamer `](https://gstreamer.freedesktop.org/)
 [` @ibus-libpinyin `](https://github.com/libpinyin/ibus-libpinyin) ` # ibus-libpinyin ibus-table-wubi `
 
 [` @realtek-network-interface-controllers-10-100-1000m-gigabit-ethernet-pci-express-software `](https://www.realtek.com/en/component/zoo/category/network-interface-controllers-10-100-1000m-gigabit-ethernet-pci-express-software) ` # lspci -v `
 
 ` @ TkIySEk0RFRISVhTNlkzT0ZaV1hHMkpPTU5YVzJMMk5ONTJHUVpMU01KWFdDNFRFRjVCREtOUlFKVVdVRVQyTklKQ1ZFTDNUT1ZZSApBMzNTT1FGQT09PT0K `
 ` @ TkIySEk0QjJGNFhXTTJUSk9OMlM0NURQT0FYUVU9PT0K ` ` @ TkIySEk0RFRISVhTNjUzVk9GVVdDM1RETjRYSFE2TDJGNEZBPT09PQo= `
 ` @ TkIySEk0RFRISVhTNjJETEZaV1hHMkpPTU5YVzJMMk5ONTJHUVpMU01KWFdDNFRFRjVCREtOUlFKVVdVRVQyTklKQ1ZFTDNUT1ZZSApBMzNTT1FGQT09PT0K `
 
 [` @breed-hackpascal `](https://breed.hackpascal.net/)
 [` @all-linux-sources `](http://mirrors.ustc.edu.cn/help/)
 [` @packages-debian `](https://packages.debian.org/)
 [` @gnu-grub `](https://ftp.gnu.org/gnu/)
 [` @tracker-debian-kernel `](https://tracker.debian.org/pkg/linux)
 [` @virtualbox `](https://download.virtualbox.org/virtualbox/)
 [` @kali-tools `](https://www.kali.org/tools/)
 [` @stream-centos `](http://mirror.stream.centos.org/)

---

## Github && Gitlab >> ssh.key && gpg.key

##### git config --global user. ``` # set.user..... ```
    
    user.email   user.signingKey
    user.name    user.useConfigOnly
      
##### git config --list
    
    --add              --fixed-value      --int              --rename-section 
    --blob=            --get              --list             --replace-all 
    --bool             --get-all          --local            --show-origin 
    --bool-or-int      --get-color        --name-only        --show-scope 
    --bool-or-str      --get-colorbool    --no-...           --system 
    --default=         --get-regexp       --no-global        --type= 
    --edit             --get-urlmatch     --null             --unset 
    --expiry-date      --global           --path             --unset-all 
    --file=            --includes         --remove-section   --worktree 
    
##### ssh-keygen -a 100 -b 4096 -t dsa/ecdsa/ecdsa-sk/ed25519/ed25519-sk/rsa -C commit [-f output_keyfile] ` # create.sshkey `
      
    -a  -C  -E  -g  -l  -n  -O  -q  -s  -u  -v  -w  -Z 
    -b  -D  -f  -h  -m  -N  -P  -r  -t  -U  -V  -z 
      
    -a rounds
             When saving a private key, this option specifies the number of
             KDF (key derivation function, currently bcrypt_pbkdf(3)) rounds
             used.  Higher numbers result in slower passphrase verification
             and increased resistance to brute-force password cracking (should
             the keys be stolen).  The default is 16 rounds. 
    -b bits
             Specifies the number of bits in the key to create.  For RSA keys,
             the minimum size is 1024 bits and the default is 3072 bits.  Gen‐
             erally, 3072 bits is considered sufficient.  DSA keys must be ex‐
             actly 1024 bits as specified by FIPS 186-2.  For ECDSA keys, the
             -b flag determines the key length by selecting from one of three
             elliptic curve sizes: 256, 384 or 521 bits.  Attempting to use
             bit lengths other than these three values for ECDSA keys will
             fail.  ECDSA-SK, Ed25519 and Ed25519-SK keys have a fixed length
             and the -b flag will be ignored. 
    -C comment
             Provides a new comment.
             
    -t dsa | ecdsa | ecdsa-sk | ed25519 | ed25519-sk | rsa
             Specifies the type of key to create.  The possible values are
             “dsa”, “ecdsa”, “ecdsa-sk”, “ed25519”, “ed25519-sk”, or “rsa”.

             This flag may also be used to specify the desired signature type
             when signing certificates using an RSA CA key.  The available RSA
             signature variants are “ssh-rsa” (SHA1 signatures, not recom‐
             mended), “rsa-sha2-256”, and “rsa-sha2-512” (the default).
      
##### ssh -T git@github.com ` # test.ssh.connect `
    
    -4  -A  -c  -e  -F  -i  -k  -L  -n  -O  -Q  -S  -v  -W  -y 
    -6  -b  -C  -E  -g  -I  -K  -m  -N  -p  -R  -t  -V  -x  -Y 
    -a  -B  -D  -f  -G  -J  -l  -M  -o  -q  -s  -T  -w  -X
    
    -T      Disable pseudo-terminal allocation.
      
##### gpg --full-generate-key ` # create.gpgkey `
      
    --full-generate-key  --full-gen-key
    
    --generate-key
    --gen-key
              Generate a new key pair using the current default  parameters.   This  is
              the standard command to create a new key.  In addition to the key a revo‐
              cation certificate is created and stored in the ‘openpgp-revocs.d’ direc‐
              tory below the GnuPG home directory.

     --full-generate-key
     --full-gen-key
              Generate  a  new  key  pair with dialogs for all options.  This is an ex‐
              tended version of --generate-key.

              There is also a feature which allows you to create keys  in  batch  mode.
              See the manual section ``Unattended key generation'' on how to use this.

    
##### gpg --list-secret-keys --keyid-format=long/short ``` # list.gpgkeyid ```
    
    --list-config         --list-options        --list-signatures
    --list-gcrypt-config  --list-packets        --list-sigs
    --list-key            --list-public-keys    --list-trustdb
    --list-keys           --list-secret-keys
    --list-only           --list-sig
      
##### gpg --list-sigs/--list-sig/--list-signatures ``` # list.gpgkeyid ```
    
    sec   rsa..../xxxxxxxxx ....-..-.. [SC]
    xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
    uid     [ultimate] uname <email>
    ssb   rsa..../xxxxxxxxxxxxxxxx xxxx-xx-xx [E]
      
##### gpg --armor/--armour --export xxxxxxxxxxxx ``` # decode.gpgkey ```
      
    --expert                 --export-options         --export-secret-subkeys
    --export                 --export-ownertrust      --export-ssh-key
    --export-filter          --export-secret-keys 
      
    --armor
       -a 
              Create ASCII armored output.  The default is to create  the  bi‐
              nary OpenPGP format.
    --export
              Either export all keys from all keyrings (default keyrings and those reg‐
              istered via option --keyring), or if at least one name is given, those of
              the given name. The exported keys are written to STDOUT or  to  the  file
              given  with  option  --output.   Use  together with --armor to mail those
              keys.

##### gpg --send-keys xxxxxxxxxxx
##### git config --global commit.gpgsign true
##### gpg --list-keys
##### git config --global user.signingkey key
##### git ls-files
    
    -c, --cached
            Show cached files in the output (default)

    -d, --deleted
            Show deleted files in the output

    -m, --modified
            Show modified files in the output

    -o, --others
            Show other (i.e. untracked) files in the output

    -i, --ignored
            Show only ignored files in the output. When showing files in the
            index, print only those matched by an exclude pattern. When showing
            "other" files, show only those matched by an exclude pattern.
             Standard ignore rules are not automatically activated, therefore at
            least one of the --exclude* options is required.
            
    -s, --stage
           Show staged contents' mode bits, object name and stage number in
           the output.

    --directory
            If a whole directory is classified as "other", show just its name
            (with a trailing slash) and not its whole contents.

    --no-empty-directory
            Do not list empty directories. Has no effect without --directory.

    -u, --unmerged
            Show unmerged files in the output (forces --stage)

    -k, --killed
            Show files on the filesystem that need to be removed due to
            file/directory conflicts for checkout-index to succeed.

    -z
            \0 line termination on output and do not quote filenames. See
            OUTPUT below for more information.

    
##### git status ``` # 0 1 2 3 ```
       
    stage    stash    status
    
##### git add README.md
##### git commit -S -m first.commit ``` # -m,--message= && -S,--gpg-sign ```
    
    --ahead-behind         --interactive          --quiet 
    --all                  --long                 --reedit-message=
    --amend                --message=             --reset-author 
    --author=              --no-...               --reuse-message=
    --branch               --no-post-rewrite      --short 
    --cleanup=             --no-verify            --signoff 
    --date=                --null                 --squash=
    --dry-run              --only                 --status 
    --edit                 --patch                --template=
    --file=                --pathspec-file-nul    --trailer=
    --fixup=               --pathspec-from-file=  --untracked-files 
    --gpg-sign             --porcelain            --verbose 
    --include              --post-rewrite         --verify
       
##### git branch -M main ``` # -M,--move --force ```
       
    --abbrev             --format=            --quiet 
    --all                --ignore-case        --remotes 
    --color              --list               --set-upstream-to=
    --column             --merged             --show-current 
    --contains           --move               --sort=
    --copy               --no-...             --track 
    --create-reflog      --no-contains        --unset-upstream 
    --delete             --no-merged          --verbose 
    --edit-description   --points-at= 
 
##### git remote add user-defined(origin) git@github.com:USERNAME/UserRepo.git || https://github.com/USERNAME/UserRepo.git
       
    add            prune          rename         set-head       show 
    get-url        remove         set-branches   set-url        update 

       
##### git push -u origin main ``` # -u,--set-upstream ```
    
    --all                  --ipv4                 --quiet
    --atomic               --ipv6                 --receive-pack=
    --delete               --mirror               --recurse-submodules=
    --dry-run              --no-...               --repo=
    --exec=                --no-verify            --set-upstream
    --follow-tags          --porcelain            --signed
    --force                --progress             --tags
    --force-if-includes    --prune                --verbose
    --force-with-lease     --push-option=         --verify

##### git push -uf origin main ``` # gitlab  -u,--set-upstream && -f,--force ``` 

---
    
## Edit.commit
  
##### git rebase -i HEAD~23 # delete.commit.23 ``` # -i,--interactive ```
       
    --apply                           --no-verify 
    --autosquash                      --onto=
    --autostash                       --quiet 
    --committer-date-is-author-date   --reapply-cherry-picks 
    --empty=                          --rebase-merges 
    --exec=                           --rerere-autoupdate 
    --ff                              --reschedule-failed-exec 
    --force-rebase                    --reset-author-date 
    --fork-point                      --root 
    --gpg-sign                        --signoff 
    --ignore-whitespace               --stat 
    --interactive                     --strategy=
    --keep-base                       --strategy-option=
    --merge                           --verbose
    --no-...                          --verify
    --no-ff                           --whitespace=
    --no-stat 
    
##### git rebase branch -i ``` # change fatal: No rebase in progress ```
##### git rebase add . ` @git rebase --continue `
##### git rebase branch -i ``` # noop >> pick ###### || # ```
##### git push github branch --force #
##### git update-ref -d HEAD ``` # reset.commit ```
    
    usage: git update-ref [<options>] -d <refname> [<old-val>]
            or: git update-ref [<options>]    <refname> <new-val> [<old-val>]
            or: git update-ref [<options>] --stdin [-z]

    -m <reason>
            reason of the update

    -d
        delete the reference

    --no-deref
        update <refname> not the one it points to
        
    -z
        stdin has NUL-terminated arguments
        
    --stdin
        read updates from stdin

    --create-reflog
        create a reflog
    
##### git reset --soft/--mixed/--hard HEAD~1/HEAD^ ``` # current > previous.commit ```
##### git reflog expire --expire=now --all ``` # clear.reflog ```
##### git gc --aggressive --prune=now
##### git reflog delete HEAD@{32} HEAD@{31} ``` # delete.reflog ```
    
     delete   expire   show
      
##### git log --all --oneline --graph ``` # view.commit ```
##### git show-branch --more --all ``` # branch.commit ```
       
    --all           --list          --no-name       --topics 
    --color         --merge-base    --reflog        --topo-order 
    --current       --more          --remotes       
    --date-order    --name          --sha1-name     
    --independent   --no-...        --sparse   
    
##### git revert commitID
       
    --cleanup=            --mainline=           --signoff 
    --commit              --no-...              --strategy=
    --edit                --no-commit           --strategy-option=
    --gpg-sign            --rerere-autoupdate 
       
---

## Journal 

##### /etc/vim/gvimrc ` >> set lines=25 columns=115 ` ` # gvim `
##### /usr/share/vim/vimrc || ` @/etc/vimrc #centos `
     
    set showmatch
    set hlsearch
    set incsearch
    set showcmd
    set number
    set mouse=a
    set autoindent
    set autowrite
    set t_Co=256 
    
    if &diff
        "colorscheme 
        highlight DiffAdd    cterm=bold ctermfg=12 ctermbg=184 gui=none guifg=bg guibg=white
        highlight DiffDelete cterm=bold ctermfg=13 ctermbg=153 gui=none guifg=bg guibg=white
        highlight DiffChange cterm=bold ctermfg=15 ctermbg=17 gui=none guifg=bg guibg=white
        highlight DiffText   cterm=bold ctermfg=11 ctermbg=none gui=none guifg=bg guibg=white
    endif

##### sudo apt install \
    
    vim vim-gtk vim-nox vim-lastplace kaffeine qbittorrent audacious calc wcalc git gitk \
    fcitx fcitx-table-compose fcitx-googlepinyin fcitx-dbus-status fcitx-table-wubi fcitx-table-wubi-large \
    wget bash-completion bash-static bash-builtins \
    basex basez base58 \
    gnome-shell-extension-dashtodock gnome-shell-extension-desktop-icons \
    nvidia-detect nvidia-smi nvidia-cg-dev
 
##### wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
##### dpkg -l |grep ^rc|awk '{print $2}' |sudo xargs dpkg -P
    
##### /usr/share/gtksourceview-4/language-specs/powershell.lang ` # gedit `
        <property name="globs">*.ps1;*.psm1;*.psd1;*.*</property>
~~sudo dpkg-reconfigure locales~~ ` # en && zh ` ` @im-config ` ` # /etc/locale.gen >> en_GB.UFT-8 UFT-8 `

##### /boot/grub/grub.cfg && /etc/default/grub ` @sudo update-grub # change.kernal `
##### systemctl enable systemd-resolved.service ` # debian `
##### /etc/inputrc  ` >> set bell-style visible ` ` # Ubuntu `

---

## /etc/hosts

    127.0.0.1	localhost xx
    127.0.1.1	xx

` # The following lines are desirable for IPv6 capable hosts `

    ::1     localhost ip6-localhost ip6-loopback
    fe00::0 ip6-localnet
    ff00::0 ip6-mcastprefix
    ff02::1 ip6-allnodes
    ff02::2 ip6-allrouters
    
    ff02::3 ip6-allhosts
    ff02::5 ip6-allospfrouters
    ff02::9 ip6-allriprouters
    ff02::A ip6-alleigrprouters

` # Node (or interface) local scope `

    ff01::1 ip6-allnode-interface
    ff01::2 ip6-allrouter-interface

` # link local scope `

    ff02::4 ip6-dvmrp-router
    ff02::6 ip6-ospf-igp-dr
    ff02::7 ip6-strouter
    ff02::8 ip6-sthost
    ff02::B ip6-mobile-agent
    ff02::D ip6-allpim-routers
    ff02::E ip6-rsvp-encapsulation
    ff02::1:1 ip6-link-name
    ff02::1:2 ip6-alldhcp-agents
    #ff05::2 ip6-allrouters-localscope-site

## /etc/NetworkManager/NetworkManager.conf

   ```
    [main]
    plugins=ifupdown,keyfile
    dns=dnsmasq
    systemd-resolved=true
    rc-manager=resolvconf
    
    [ifupdown]
    managed=true

    [device]
    wifi.scan-rand-mac-address=yes
    
    [connectivity]
    uri=
    interval=0
    
   ```
## /etc/systemd/resolved.conf >> systemctl restart systemd-resolved.service && resolvectl

   ```
    DNS= 2606:4700:4700::1001 2606:4700:4700::1111 2001:4860:4860::8888 2001:4860:4860::8844 2620:fe::9 2620:fe::fe:9 2a09:: 2a11:: 2620:119:53::53 2620:119:35::35 2001:dc7:1000::1 240c:f:1:22::6 2001:de4::101 2001:de4::102 2001:da8:8000:1:202:120:2:100 2001:da8:8000:1:202:120:2:101 2001:da8:ff:305:20c:29ff:fe1f:a92a 2a02:6b8::feed:ff 2a02:6b8:0:1::feed:ff 2a02:6b8::feed:bad 2a02:6b8:0:1::feed:bad 2620:fe::fe 2620:fe::9 2620:0:ccc::2 2620:0:ccd::2
    FallbackDNS= 1.2.4.8 223.5.5.5 5.5.5.223 223.6.6.6 180.76.76.76 119.29.29.29 52.80.66.66 101.226.4.6 218.30.118.6 123.125.81.6 140.207.198.6 1.1.1.1 1.0.0.1 8.8.8.8 8.8.4.4 9.9.9.9 185.222.222.222 185.184.222.222 208.67.222.222 208.67.220.220 178.79.131.110 119.29.29.29

    Domains=lan
    DNSSEC=allow-downgrade
    DNSOverTLS=opportunistic
    MulticastDNS=yes
    LLMNR=yes
    
   ```
---

