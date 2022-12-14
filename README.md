[ja](./README.ja.md)

# CSharp.DotNet6.Override.Overload

Experiment with overriding and overloading in C#.

# DEMO

* [demo](https://ytyaru.github.io/CSharp.CSharp.DotNet6.Override.Overload.20220926142101/)

![img](https://github.com/ytyaru/CSharp.CSharp.DotNet6.Override.Overload.20220926142101/blob/master/doc/0.png?raw=true)

# Features

* sales point

# Requirement

* <time datetime="2022-09-26T14:20:58+0900">2022-09-26</time>
* [Raspbierry Pi](https://ja.wikipedia.org/wiki/Raspberry_Pi) 4 Model B Rev 1.2
* [Raspberry Pi OS](https://ja.wikipedia.org/wiki/Raspbian) buster 10.0 2020-08-20 <small>[setup](http://ytyaru.hatenablog.com/entry/2020/10/06/111111)</small>
* bash 5.0.3(1)-release
* dotnet 6.0.401

```sh
$ uname -a
Linux raspberrypi 5.10.103-v7l+ #1529 SMP Tue Mar 8 12:24:00 GMT 2022 armv7l GNU/Linux
```

# Installation

```sh
NAME=dotnet-sdk-6.0.401-linux-arm.tar.gz
wget https://download.visualstudio.microsoft.com/download/pr/451f282f-dd26-4acd-9395-36cc3a9758e4/f5399d2ebced2ad9640db6283aa9d714/$NAME
tar -zxvf $NAME
```

~/.bashrc
```sh
export PATH=$PATH:$HOME/some/.NETCore/6.0.401
```

# Usage

```bash
git clone https://github.com/ytyaru/CSharp.CSharp.DotNet6.Override.Overload.20220926142101
cd CSharp.CSharp.DotNet6.Override.Overload.20220926142101
./run.sh
```

# Author

ytyaru

* [![github](http://www.google.com/s2/favicons?domain=github.com)](https://github.com/ytyaru "github")
* [![hatena](http://www.google.com/s2/favicons?domain=www.hatena.ne.jp)](http://ytyaru.hatenablog.com/ytyaru "hatena")
* [![twitter](http://www.google.com/s2/favicons?domain=twitter.com)](https://twitter.com/ytyaru1 "twitter")
* [![mastodon](http://www.google.com/s2/favicons?domain=mstdn.jp)](https://mstdn.jp/web/accounts/233143 "mastdon")

# License

This software is CC0 licensed.

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.en)

