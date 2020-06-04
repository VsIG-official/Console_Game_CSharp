# Tetris Game

<a href="https://github.com/VsIG-official/ConsoleGameCSharp/blob/Another-One/Images/1.png"><img src="https://github.com/VsIG-official/ConsoleGameCSharp/blob/Another-One/Images/1.png" title="VsIG" alt="VsIG"></a>

## Table of Contents (Optional)

- [Description](#description)
- [Badges](#badges)
- [Contributing](#contributing)
- [License](#license)

### Description

> Hi, My dear Friend! In this repo You'll see console tetris game! Why tetris? Well, I decided to make a tetris because I love tetris! In this project I use C# and Visual Studio. Hope You will enjoy!

## Badges

I use codacy to check My code quality:
[![Code Quality](http://img.shields.io/travis/badges/badgerbadgerbadger.svg?style=flat-square)](https://travis-ci.org/badges/badgerbadgerbadger)
[![Language](https://img.shields.io/badge/Language-C%23-blueviolet)]
[![Theme](https://img.shields.io/badge/Game-Tetris-red](https://en.wikipedia.org/wiki/Tetris)

---

## Example

```C#

public void MoveRight(ref char[][] tetrisGrid, char shapes, char freeSpace)
		{
			for (int i = 0; i < matrixWidth; i++)
			{
				for (int j = matrixHeight - 1; j >= 0; j--)
				{
					if (tetrisGrid[i][j] == shapes && tetrisGrid[i][j + 1] == freeSpace)
					{
						char tempMatrix = tetrisGrid[i][j];
						tetrisGrid[i][j] = tetrisGrid[i][j + 1];
						tetrisGrid[i][j + 1] = tempMatrix;
					}
				}
			}
		}
```

<a href="https://github.com/VsIG-official/ConsoleGameCSharp/blob/Another-One/Images/2.gif"><img src="https://github.com/VsIG-official/ConsoleGameCSharp/blob/Another-One/Images/2.gif" title="VsIG" alt="VsIG"></a>

---

## Contributing

> To get started...

### Step 1

    - 🍴 Fork this repo!

### Step 2

- **HACK AWAY!** 🔨🔨🔨

---

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- My telegram https://t.me/VsIG_official
- Copyright 2020 © <a href="https://github.com/VsIG-official" target="_blank">VsIG</a>.