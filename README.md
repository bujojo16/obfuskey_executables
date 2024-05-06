# obfuskey\_executables
Standalone package for running Obfuskey without Python 3.11 installed.

***

The executable files found in this repository were made using PyInstaller on the latest version of [Obfuskey](https://github.com/bujojo16/obfuskey). They are meant as a user-friendly way of running Obfuskey without bothering installing Python 3.11. It is recommended to read the documentation located in the Obfuskey repository before running any of the executables in here.


For absolute security, it is recommended you read the source code from Obfuskey's repository (so you can make sure it is safe), clone it and generate your own version using PyInstaller. This will improve compatibility since it is made using your own operating system and will give you the opportunity to make sure your executable was generated from the original Obfuskey source code.

## How to use
### Tails Os/Linux:
- Download the ZIP file of the repository and UNZIP it in the folder where it is located (Tails: 'Tor Browser')   
- Open a terminal and type:
```bash
cd <path/to/directory>/obfuskey_executables
chmod +x obfuskey-2.1_linux
./obfuskey-2.1_linux
```
You will need to add the execution permission to the file in order to run it, which is done using the chmod command as mentioned above.
### Windows:
- Download the ZIP file of the repository and UNZIP it in a folder   
    or  
- clone the repository
- Simply run the .exe file

You will need to keep the file structure to run Obfuskey, meaning the Mnemonics directory must be in the same directory as the executable. If you need to add another mnemonic, add it to the Mnemonics directory.

The output of the obfuscation will be a text file found in the "Output" directory, created by the program.

## Version compatibility
All executables are created using a cleaned-up system and PyInstaller. Because PyInstaller doesn't include some of the basic operating system's packages (GLIBC in Linux's case for example), version compatibility can be tricky. If you want to make your own executables working on your specific operating system, please clone the original Obfuskey repo and create your own executables using PyInstaller with your operating system's version.
### Current versions:
#### Windows:
Created using Windows 10. Works with Windows 10. Should work with Windows 11.
#### Linux:
Created using Ubuntu 24.04. Works with Tails 6.2. Because of GLIBC version, compatibility with older systems won't be straight forward. Your best option is to update to these versions at least.

