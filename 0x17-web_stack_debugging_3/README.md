0x17. Web stack debugging #3
Install puppet-lint

$ apt-get install -y ruby
$ gem install puppet-lint -v 2.1.1

0. Strace is your friend

Using strace, find out why Apache is returning a 500 error. Once you find the issue, fix it and then automate it using Puppet (instead of using Bash as you were previously doing).

Requirements:

    Your 0-strace_is_your_friend.pp file must contain Puppet code
    You can use whatever Puppet resource type you want for you fix
