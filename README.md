# My Dotfiles

Note to self:

    ∴ git clone git://github.com/lawrencepit/dotfiles.git ~/.dotfiles
    ∴ cd ~/.dotfiles
    ∴ rvm gemset create dotfiles
    ∴ rvm gemset use dotfiles
    ∴ gem install rake bundler
    ∴ bundle install
    ∴ rake

Dotfile
Gemfile
Gemfile.lock
README.md
Rakefile
bin
config
total 192
<<<<<<< HEAD
drwxr-xr-x   30 hoanghan  staff   1.0K Oct 10 16:50 .
drwxr-xr-x  163 hoanghan  staff   5.4K Oct 10 16:50 ..
-rw-r--r--    1 hoanghan  staff   3.4K Oct 10 16:50 .bash_aliases
-rw-r--r--    1 hoanghan  staff   707B Oct 10 16:50 .bash_colors
-rw-r--r--    1 hoanghan  staff   124B Oct 10 16:50 .bash_profile
-rw-r--r--    1 hoanghan  staff   842B Oct 10 16:50 .bash_prompt
-rw-r--r--    1 hoanghan  staff   400B Oct 10 16:50 .bashrc
drwxr-xr-x    3 hoanghan  staff   102B Oct 10 16:50 .bundle
-rw-r--r--    1 hoanghan  staff   623B Oct 10 16:50 .bundle_exec
-rw-r--r--    1 hoanghan  staff   120B Oct 10 16:50 .curlrc
-rw-r--r--    1 hoanghan  staff   1.8K Oct 10 16:50 .exports
-rw-r--r--    1 hoanghan  staff   608B Oct 10 16:50 .functions
-rw-r--r--    1 hoanghan  staff   158B Oct 10 16:50 .gemrc.erb
drwxr-xr-x   13 hoanghan  staff   442B Oct 10 16:51 .git
-rw-r--r--    1 hoanghan  staff   3.8K Oct 10 16:50 .gitconfig.erb
-rw-r--r--    1 hoanghan  staff   1.6K Oct 10 16:50 .irbrc
-rw-r--r--    1 hoanghan  staff   3.0K Oct 10 16:50 .osx
-rw-r--r--    1 hoanghan  staff   125B Oct 10 16:50 .profile
-rw-r--r--    1 hoanghan  staff   2.0K Oct 10 16:50 .reerc
-rw-r--r--    1 hoanghan  staff     9B Oct 10 16:50 .ruby-gemset
-rw-r--r--    1 hoanghan  staff    11B Oct 10 16:50 .ruby-version
-rw-r--r--    1 hoanghan  staff   758B Oct 10 16:50 .spotlight
-rw-r--r--    1 hoanghan  staff   1.0K Oct 10 16:50 .truecrypt
-rw-r--r--    1 hoanghan  staff   266B Oct 10 16:50 Dotfile
-rw-r--r--    1 hoanghan  staff    76B Oct 10 16:50 Gemfile
-rw-r--r--    1 hoanghan  staff   276B Oct 10 16:50 Gemfile.lock
-rw-r--r--    1 hoanghan  staff   321B Oct 10 16:50 README.md
-rw-r--r--    1 hoanghan  staff   2.1K Oct 10 16:50 Rakefile
drwxr-xr-x   23 hoanghan  staff   782B Oct 10 16:50 bin
drwxr-xr-x    3 hoanghan  staff   102B Oct 10 16:50 config
=======
drwxr-xr-x   30 hoanghan  staff   1.0K Oct 10 16:51 .
drwxr-xr-x  163 hoanghan  staff   5.4K Oct 10 16:50 ..
-rw-r--r--    1 hoanghan  staff   3.4K Oct 10 16:25 .bash_aliases
-rw-r--r--    1 hoanghan  staff   707B Oct 10 16:25 .bash_colors
-rw-r--r--    1 hoanghan  staff   124B Oct 10 16:25 .bash_profile
-rw-r--r--    1 hoanghan  staff   842B Oct 10 16:25 .bash_prompt
-rw-r--r--    1 hoanghan  staff   400B Oct 10 16:46 .bashrc
drwxr-xr-x    3 hoanghan  staff   102B Oct 10 16:25 .bundle
-rw-r--r--    1 hoanghan  staff   623B Oct 10 16:25 .bundle_exec
-rw-r--r--    1 hoanghan  staff   120B Oct 10 16:25 .curlrc
-rw-r--r--    1 hoanghan  staff   1.8K Oct 10 16:25 .exports
-rw-r--r--    1 hoanghan  staff   608B Oct 10 16:25 .functions
-rw-r--r--    1 hoanghan  staff   158B Oct 10 16:25 .gemrc.erb
drwxr-xr-x   16 hoanghan  staff   544B Oct 10 16:51 .git
-rw-r--r--    1 hoanghan  staff   3.8K Oct 10 16:25 .gitconfig.erb
-rw-r--r--    1 hoanghan  staff   1.6K Oct 10 16:25 .irbrc
-rw-r--r--    1 hoanghan  staff   3.0K Oct 10 16:25 .osx
-rw-r--r--    1 hoanghan  staff   125B Oct 10 16:25 .profile
-rw-r--r--    1 hoanghan  staff   2.0K Oct 10 16:25 .reerc
-rw-r--r--    1 hoanghan  staff     9B Oct 10 16:25 .ruby-gemset
-rw-r--r--    1 hoanghan  staff    11B Oct 10 16:25 .ruby-version
-rw-r--r--    1 hoanghan  staff   758B Oct 10 16:25 .spotlight
-rw-r--r--    1 hoanghan  staff   1.0K Oct 10 16:25 .truecrypt
-rw-r--r--    1 hoanghan  staff   266B Oct 10 16:25 Dotfile
-rw-r--r--    1 hoanghan  staff    76B Oct 10 16:25 Gemfile
-rw-r--r--    1 hoanghan  staff   276B Oct 10 16:25 Gemfile.lock
-rw-r--r--    1 hoanghan  staff   321B Oct 10 16:51 README.md
-rw-r--r--    1 hoanghan  staff   2.1K Oct 10 16:25 Rakefile
drwxr-xr-x   23 hoanghan  staff   782B Oct 10 16:25 bin
drwxr-xr-x    3 hoanghan  staff   102B Oct 10 16:25 config
>>>>>>> e481e9a0d541672bcded9cabf13dc2a5f98ab45c
total 192
drwxr-xr-x   30 hoanghan  staff   1.0K Oct 10 16:53 .
drwxr-xr-x  163 hoanghan  staff   5.4K Oct 10 16:50 ..
-rw-r--r--    1 hoanghan  staff   3.4K Oct 10 16:50 .bash_aliases
-rw-r--r--    1 hoanghan  staff   707B Oct 10 16:50 .bash_colors
-rw-r--r--    1 hoanghan  staff   124B Oct 10 16:50 .bash_profile
-rw-r--r--    1 hoanghan  staff   842B Oct 10 16:50 .bash_prompt
-rw-r--r--    1 hoanghan  staff   400B Oct 10 16:50 .bashrc
drwxr-xr-x    3 hoanghan  staff   102B Oct 10 16:50 .bundle
-rw-r--r--    1 hoanghan  staff   623B Oct 10 16:50 .bundle_exec
-rw-r--r--    1 hoanghan  staff   120B Oct 10 16:50 .curlrc
-rw-r--r--    1 hoanghan  staff   1.8K Oct 10 16:50 .exports
-rw-r--r--    1 hoanghan  staff   608B Oct 10 16:50 .functions
-rw-r--r--    1 hoanghan  staff   158B Oct 10 16:50 .gemrc.erb
drwxr-xr-x   15 hoanghan  staff   510B Oct 10 16:55 .git
-rw-r--r--    1 hoanghan  staff   3.8K Oct 10 16:50 .gitconfig.erb
-rw-r--r--    1 hoanghan  staff   1.6K Oct 10 16:50 .irbrc
-rw-r--r--    1 hoanghan  staff   3.0K Oct 10 16:50 .osx
-rw-r--r--    1 hoanghan  staff   125B Oct 10 16:50 .profile
-rw-r--r--    1 hoanghan  staff   2.0K Oct 10 16:50 .reerc
-rw-r--r--    1 hoanghan  staff     9B Oct 10 16:50 .ruby-gemset
-rw-r--r--    1 hoanghan  staff    11B Oct 10 16:50 .ruby-version
-rw-r--r--    1 hoanghan  staff   758B Oct 10 16:50 .spotlight
-rw-r--r--    1 hoanghan  staff   1.0K Oct 10 16:50 .truecrypt
-rw-r--r--    1 hoanghan  staff   266B Oct 10 16:50 Dotfile
-rw-r--r--    1 hoanghan  staff    76B Oct 10 16:50 Gemfile
-rw-r--r--    1 hoanghan  staff   276B Oct 10 16:50 Gemfile.lock
-rw-r--r--    1 hoanghan  staff   4.0K Oct 10 16:53 README.md
-rw-r--r--    1 hoanghan  staff   2.1K Oct 10 16:50 Rakefile
drwxr-xr-x   23 hoanghan  staff   782B Oct 10 16:50 bin
drwxr-xr-x    3 hoanghan  staff   102B Oct 10 16:50 config
