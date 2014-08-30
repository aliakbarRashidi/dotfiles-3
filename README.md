dotfiles
========

My dotfiles synced with rcm.

installation
------------
- Install RCM
```
wget https://thoughtbot.github.io/rcm/debs/rcm_1.2.3-1_all.deb;
sudo dpkg -i rcm_1.2.3-1_all.deb;
rm rcm_1.2.3-1_all.deb;
```

Or install with non-dpkg systems [here](https://github.com/thoughtbot/rcm).
- Clone repo
```
git clone git@github.com:bezi/dotfiles.git ~/.dotfiles;
cd .dotfiles;
git submodule update --init --recursive; # get submodules
```

- Check that all is well and propagate .dotfiles
```
lsrc;
rcup;
```

For best results, also install [Sauce Code Powerline](https://github.com/Lokaltog/powerline-fonts/tree/master/SourceCodePro) for vim.
