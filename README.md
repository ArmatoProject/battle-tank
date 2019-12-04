# Armato 💥

## Introduction
Armato is a shooter genre game based on the 90's "Battle Tank". The name **Armato** itself comes from the italian _carro armato_ which means _tank_ in english. The purpose of build this project is for learning data structure with c++ language, and working with team in project course in JTK Polban.

## How to Setup
This project using Code::Blocks IDE, so these setup steps following Code::Blocks structure project and compiler.
### Setting graphics.h
1. Download WinBGIm from http://winbgim.codecutter.org/
2. Extract the downloaded file. There will be three files:
    - graphics.h
    - winbgim.h
    - libbgi.a
3. Copy and paste ```graphics.h``` and ```winbgim.h``` to the **include** folder of compiler directory.
    ```
    C:/ProgramFiles(x86)/CodeBlocks/MinGW/include
    ```
4. Copy and paste ```libbgi.a``` to the **lib** folder of compiler directory.
    ```
    C:/ProgramFiles(x86)/CodeBlocks/MinGW/lib
    ```
5. Open Code::Blocks IDE. Go to Settings >> Compiler >> Linker settings. New window will appear, click the Add button under the _Link libraries_ part and browse to select the ```libbgi.a``` file.
6. Fill the _Other linker optios_ with commands
    ```
    -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
    ```

**Note** : While compiling still there will be an error. To solve it open graphics.h with your text editor. Go to **line number 302** and replace that line with this line ```int left=0, int top=0, int right=INT_MAX, int bottom=INT_MAX,``` and save the file.

## Who are the teams
- Agit Prasetya - [@AgitPrasetya](https://github.com/AgitPrasetya)
- Faatih Syauqi - [@FaatihSyauqi](https://github.com/FaatihSyauqi)
- Kartika Sari - [@Kartikaaa](https://github.com/Kartikaaa)
- Mughie Arief - [@mughieams](https://github.com/mughieams/)
- Novilawati - [@Novilawati14](https://github.com/Novilawati14)

With ♥️ from Ciwaruga

🐳
