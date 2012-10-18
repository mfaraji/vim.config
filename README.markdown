
Prerequisites
=============

You will need the following things installed proceedng:

1. Ruby (strange, I know)

2. Rake

3. MacVim (if you are on the Mac)

Installation
============

1. Check out the package: 

				cd ~/.vim
				git clone https://github.com/mfaraji/vim.config

2. Install vundler: 

				git clone http://github.com/gmarik/vundle.git ~/.vim/bundle/vundle


3. Install the bundles using vundler: 

				vim
				:BundleInstall!

4. Compile the Command-T plugin

				cd ~/.vim/bundle/Command-T
				rake make

