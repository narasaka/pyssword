pyssword
========
cute lil password generator/manager(local)
the passwords generated will be automatically copied to your clipboard so you can simply paste it anywhere.
luv u.
- - - -


## Installation ##
    
    git clone https://github.com/narasaka/pyssword.git
    cd pyssword
    sudo dpkg -i pyssword_v0.0.1.deb
    
    pyssword --version
    
### Usage ###
    
    pyssword
    
    Usage: password [options] [username] [platform] [password]

    -----

    Example to set password: password -s nathnaeltg instagram p455w0rd
    Example to get password: password -g nathnaeltg instagram
    Example to get list of usernames: password -l

    -----

    Options list:

    -h or --help: displays guide
    -s or --set: change mode to "set"
    -f or --fetch: change mode to "fetch". Copies password to clipboard.
    -g or --generate change mode to "generate"
    -l or --list: displays a list of platforms/usernames
    -v or --version: this one is pretty straightforward...

- - - -
    
    pyssword -g narasaka github
    
    Type "r" for a strong random password
    Type "d" for a diceware type password
    Type "an" for an alphanumeric password
    Input: r
    Length of password(make it long!)[int]: 22
    Your password will be 22 characters long.
    [Y] to proceed, [n] to cancel: y
    Generating...

    Your password is copied to clipboard. Go ahead and paste it.

- - - -
    
    pyssword -f narasaka github
    
    
    Your password is copied to clipboard. Go ahead and paste it.

- - - -
    
