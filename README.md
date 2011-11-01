ssh_connect is a console bookmark tool to connect quickly to your most
used ssh servers.

# Usage

    git clone git://github.com/alx/ssh_connect.git
    cp ssh_connect/ssh_connect ~/bin
    cp ssh_connect/servers.yaml.example ~/.ssh_connect
    ssh_connect

Then select the server you want to connect to.

# Faster

    ssh_connect 1 # connect to the first server on the list

# Tips

Add an alias to your bash:

    alias s='ssh_connect'
