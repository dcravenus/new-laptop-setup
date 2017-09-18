Install Chrome

Chrome Extensions
https://adblockplus.org/
http://www.editthiscookie.com/
https://www.eff.org/privacybadger
https://chrome.google.com/webstore/detail/quick-javascript-switcher/geddoclleiomckbhadiaipdggiiccfje?hl=en
https://chrome.google.com/webstore/detail/advanced-profanity-filter/piajkpdbaniagacofgklljacgjhefjeh?hl=en

Install Homebrew
https://brew.sh/
Brew Packages
	git
		Add path to .bash_profile
		export PATH=/usr/local/git/bin:$PATH # Use brew's git instead of Apple Git
	bash-completion
		Remember to paste the bash profile bit



Install Spectacle

Download Peppermint Terminal theme
https://noahfrederick.com/log/lion-terminal-theme-peppermint
Set as default
Set terminal to auto-close

Add colors and ls stuff to bash profile - and 
nano ~/.bash_profile

export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\h:\[\033[33;1m\]\w\[\033[m\]\$ "
export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
alias ls='ls -GFh'


Add ll alias to bash profile
alias ll='ls -lG'

nvm
https://github.com/creationix/nvm#install-script
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.4/install.sh | bash




Install Sublime
https://www.sublimetext.com/
Symlink subl
ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/

Package Control
https://packagecontrol.io/installation




FS Specific

Install Slack

Chrome Extension
https://chrome.google.com/webstore/detail/fs-session-id/jdbialpeookhgmmalmcofakfgjdfhpmf