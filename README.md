  ```
  /    --

    :bin --
        ::dev --   
            :::lib --
        ::libx32  --
    :mnt  --
        ::root  --
            :::snap  --     
        ::sys  -- 
    :var  --
        ::boot  -- 
            :::etc  --
        ::lib32  --
    :lost+found  --
        ::opt  --
            :::run  --
        ::srv  --
    :tmp  --
        ::cdrom  --
            :::home  --
        ::lib64  --
    :media  --
        ::proc  --
            :::sbin  --
        ::swapfile  --
    :usr  --
    
  ```
---
***    

#      https://www.webcrawler.com/
#      https://yandex.com/
#      https://kernel.ubuntu.com/~kernel-ppa/mainline/
#      https://www.wolframalpha.com/
#      https://git-scm.com/
#      https://cdn.kernel.org/pub/linux/kernel/v5.x/
#      https://md5hashing.net/hash
#      https://md5calc.com/hash

---
***

      git config --global user.
        user.email           user.signingKey      
        user.name            user.useConfigOnly
      git config --list
      ssh-keygen -t rsa -C "email" [-f output_keyfile]
      ssh -T git@github.com
      gpg --full-generate-key
      gpg --list-secret-keys --keyid-format=long
        sec   rsa..../xxxxxxxxx ....-..-.. [SC]
           xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
        uid                 [ultimate] uname <email>
        ssb   rsa..../xxxxxxxxxxxxxxxx xxxx-xx-xx [E]
      gpg --armor --export xxxxxxxxxxxx
      gpg --send-keys xxxxxxxxxxx
      git config --global user.signingkey xxxxxxxxxxx
      git config commit.gpgsign true
      git config --global commit.gpgsign true
      gpg --list-keys
      git config --global user.signingkey key
      git ls-files git status
      git add README.md
      git commit -m "first.commit"
      git branch -M main
      git remote origin git@github.com:gitLoginName/repo.git
      git push -u origin main
      git push origin main

---
***

      /etc/vim/gvimrc set lines=25 columns=115
      sudo apt install kaffeine qbittorren audacious iftop calc wcalc
      wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
      dpkg -l |grep ^rc|awk '{print $2}' |sudo xargs dpkg -P 
      /usr/share/gtksourceview-4/language-specs/html.lang <property name="globs">*.html;*.htm;*;</property>

---
***

     DNS= 2606:4700:4700::1001 2606:4700:4700::1111 2001:4860:4860::8888 2001:4860:4860::8844 2620:fe::9 2620:fe::fe:9 2a09:: 2a11:: 2620:119:53::53 2620:119:35::35 2001:dc7:1000::1 240c:f:1:22::6 2001:de4::101 2001:de4::102 2001:da8:8000:1:202:120:2:100 2001:da8:8000:1:202:120:2:101 2001:da8:ff:305:20c:29ff:fe1f:a92a 2a02:6b8::feed:ff 2a02:6b8:0:1::feed:ff 2a02:6b8::feed:bad 2a02:6b8:0:1::feed:bad 2620:fe::fe 2620:fe::9 2620:0:ccc::2 2620:0:ccd::2 

     FallbackDNS= 1.2.4.8 223.5.5.5 5.5.5.223 223.6.6.6 180.76.76.76 119.29.29.29 52.80.66.66 101.226.4.6 218.30.118.6 123.125.81.6 140.207.198.6 1.1.1.1 1.0.0.1 8.8.8.8 8.8.4.4 9.9.9.9 185.222.222.222 185.184.222.222 208.67.222.222 208.67.220.220 178.79.131.110 119.29.29.29

      Domains=lan
      DNSSEC=allow-downgrade
      DNSOverTLS=opportunistic
      MulticastDNS=yes
      LLMNR=yes
---
***









