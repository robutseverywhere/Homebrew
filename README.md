# Homebrew

[Homebrew Official Website](https://brew.sh)

[Homebrew on Github](https://github.com/Homebrew/brew)


## A big thank you to reddit user u/Serif for the majority of this list.

# Useful Brew commands.

brew cask install spotify slack visual-studio-code - How to install applications you might want.

brew update - Update brew itself and fetches info about what's available for your other software.

brew upgrade - Upgrade/update everything you've installed with Homebrew.

brew list - Display software you've installed.

brew cask list - Display GUI apps you've installed.

brew cask upgrade - Update GUI apps you've installed (u/_zio_pane).

brew outdated - Display available updates.

brew upgrade whatever_package - Upgrade only a specific thing.

brew cleanup - Remove old versions.

brew leaves - Shows only packages you installed without their dependencies.

brew analytics off - To opt out of google analytics.


# Other random things you can install with Homebrew. (to install any of these, it's brew install whatever)

youtube-dl - Download video or audio from YouTube - (and a LOT of other sites (u/frozenpandaman)).

ffmpeg - media transcoder - Youtube-dl uses this automatically if the format you want from YouTube isn't directly available.

tldr - More useful and to-the-point way to get info and example uses for commands (better than digging through 100 pages with man).

gnu-typist - Fun typing tutor. I used this when I switched from QWERTY to Colemak layout, but someone could have fun with this just to get faster with the regular QWERTY layout.

neofetch - Shows OS and shell info, you see this a lot in r/unixporn screenshots (by the way, macOS is a real, certified Unix, with BSD heritage).

rename - Better than mv for batch-renaming files.

fortune - Gives you your fortune for the day/moment.

cowsay - Have a cow say things - fortune | cowsay will let the cow provide your fortune.

coreutils - The official GNU versions of core utilities like mv, cp, ls, chown, chroot, cat, head, etc, so you can be sure they behave in exactly the same way as on Linux and other systems.

bash-completion - Or you can just make bash itself better with this.

iterm2 - A better Terminal (GUI app)

links and lynx - Text mode browsers

neovim - A slightly better vim (text editor), but you can also just install vim to get a newer version than what ships with macOS.

flac and opus - media codecs, and mpv - A media player.

sox - Also automatically installs the tool/command play which can play media directly in the terminal, as simple as play song.mp3 or play *.mp3 to play a whole folder, one at a time. It can also synthesize white or pink noise, and apply filters. For example, this is great at blocking speech by mimicking the sound of hundreds of people talking in a coliseum (plus a fountain, maybe), to help you focus:

play -c 2 -n synth pinknoise mix synth sine amod 0.07 90 band -n 2000 1q vol 0.9

-c 2 - Creates two channels (stereo) (not needed when playing a file that's already stereo)

-n synth pinknoise - Makes it synthesize pink noise.

mix synth sine amod 0.07 90 - Makes it slowly cycle loudness between 100% and 90% at a rate of 0.07 cycles per second (a little over 14 seconds for a full cycle)
band -n 2000 1q creates a bandpass filter centered at 2khz with a "Q" of one, where lower numbers (like 0.5) make it more relaxed/wider and higher numbers (like 2 or 4) make it tighter

vol 0.9 - Sets the volume to 90%.
