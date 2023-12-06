1. First make sure you have vim installed. 
2. Then install vim plugged from this url "https://github.com/junegunn/vim-plug" 
3. Then you will place the contents of this folder into /home/"username"/.vim
DO NOT PLACE THE .VIM FOLDER INTO .VIM JUST THE CONTENTS OF .VIM
4. Make sure to delete the default .vimrc and .viminfo before step 5.
5. Then you will put the .vimrc & .viminfo into /home/"username"
6. Once you have  .vimrc, .viminfo, and .vim into the right spots, go into the
.vimrc file and do :PlugUpgrade and :PlugUpdate "nameOfPlugin". Note the space
between the plugin name and :PlugUpdate.
7. Finally everything should work if not then you messed up something or you
forgot to do step 6 for all plugins. 

PLEASE NOTE :PlugUpgrade will update vim-plug itself if fresh install you should be fine skiping
