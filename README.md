# Header for VSCode

This extension provides the 101 header integration in VS Code.

```bash
********************************************************************************
*                                                                              *
*                                                                              *
*    get_next_line.c                                                           *
*                                                                              *
*    By: lmistie <romaniy11052001@gmail.com>                                   *
*                                                                              *
*    Created: 2022/04/22 17:36 by lmistie                                      *
*    Updated: 2022/04/22 17:56 by lmistie                                      *
*                                                                              *
*                                                                              *
********************************************************************************
```

## Install

Launch Quick Open with <kbd>⌘</kbd>+<kbd>P</kbd> and enter
```
ext install 101header
```

## Usage

### Insert a header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

Header is automatically updated on save.


## Configuration

Default values for **username** and **email** are imported from environment variables.

To override these values, specify these properties in *User Settings* :

```ts
{
  "101header.username": string,
  "101header.email": string
}
```


## License

MIT
