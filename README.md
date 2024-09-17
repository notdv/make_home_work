# make_home_work

'Make' homework

## Usage

### Configuration

1) Init autotools
    ```aclocal```

2) Generate config.
    ```autoconf```

3) Generate the Makefile.in.
    ```automake --add-missing```

4) Configure envinronment and generate Makefile.
    ```./configure```

### Install

1) Build the project.
    ```make```

2) Install.
    ```sudo make install```

3) Clean and uninstall.
    ```sudo make clean-all```
