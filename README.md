# ubuntu20mode

Run apps on Ubuntu 20.04 mode

在 Ubuntu 使用旧版 Ubuntu 20.04 模式运行 apps

# Initialize

    wget https://github.com/shellexy/ubuntu20mode/raw/main/ubuntu20mode
    bash ubuntu20mode init

# Usage

    ubuntu20mode run                    # run a command in ubuntu 20.04 mode
    ubuntu20mode bash                   # run bash shell in ubuntu 20.04 mode
    ubuntu20mode files     <file(s)>    # show on file manager
    ubuntu20mode apps                   # show app launcher
    ubuntu20mode list                   # list installed packages
    ubuntu20mode search    <keyword(s)> # search in package descriptions
    ubuntu20mode show      <package(s)> # show package details
    ubuntu20mode install   <package(s)> # install packages
    ubuntu20mode remove    <package(s)> # remove packages
    ubuntu20mode update                 # update list of available packages
    ubuntu20mode upgradeable            # list upgradeable packages
    ubuntu20mode upgrade                # upgrade the system by installing/upgrading packages
    ubuntu20mode upgrade_self           # upgrade this tool
    ubuntu20mode update_desktop_menu    # update of the app launcher menu
    ubuntu20mode COMMAND                # run a command in ubuntu 20.04 mode


# Example

    ubuntu20mode apps                   # show app launcher
    ubuntu20mode files                  # show on file manager
    ubuntu20mode notepad                # launch a text editor
    ubuntu20mode search wiki editor     # search a wiki app
    ubuntu20mode install zim            # install the zim wiki app
    ubuntu20mode zim                    # run the desktop wiki app
    ubuntu20mode bash
