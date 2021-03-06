# idenLib.py

[`idenLib`](https://github.com/secrary/idenLib) (Library Function Identification ) plugin for `IDA Pro`

![ida_boost_2](https://user-images.githubusercontent.com/16405698/52437166-1bf3a680-2b0e-11e9-8212-7f017757133b.gif)

## Usage
- Copy the plugin under `plugins` folder
- Copy signatures under `SymEx` folder
- Install dependencies: [`zstd`](https://pypi.org/project/zstd/) and [`capstone`](https://pypi.org/project/capstone/) (`pip2 install zstd capstone`)

- You need to refresh signatures after adding new signature files
![refresh](https://user-images.githubusercontent.com/16405698/53285741-15933a80-375c-11e9-97cb-d38bb0b5c52e.png)


## Credits
- Disassembly powered by [Capstone](https://www.capstone-engine.org/)
- Decompressing powered by [zstd](https://github.com/facebook/zstd)
- Icon by [freepik](https://www.flaticon.com/authors/freepik)
