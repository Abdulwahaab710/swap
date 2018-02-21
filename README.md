# Swap
Swap allows you to swap the name of two files

## Installation

```bash
git clone git@github.com:Abdulwahaab710/swap.git
```
### Bash
```bash
echo "export PATH=\$PATH:$(pwd)/swap" >> ~/.bashrc
```

### zsh
```zsh
echo "export PATH=\$PATH:$(pwd)/swap" >> ~/.zshrc
```

## Usage:
we have a file `x`
```bash
$ echo "x" > x
```
and a file `y`
```bash
$ echo "y" > y
```
So now to swap the name of the two files, we run the following:
```bash
$ swap x y
```
This will swap `x` name with `y`, so if we output x and y we get:
```bash
$ cat x
y
```
```bash
$ cat y
x
```

## License

```
Copyright (c) 2018 Abdulwahaab Ahmed

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
