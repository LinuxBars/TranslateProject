如何在Linux中安装漂亮的扁平化Arc GTK+主题
================================================================================
> 易于看懂的每步都有的教程

**今天我们将向你介绍最新发布的GTK+主题，它拥有透明和扁平元素，并且与多个桌面环境和Linux发行版见荣发。[这个主题叫Arc][1]。**

开始讲细节之前，我建议你快速地看一下下面的图，这样你有会对这个主题就会有一个基本的概念了。同样你应该意识到它目前可以工作在GTK+ 2.x、GTK+ 3.x、GNOME-Shell、 Budgie、 Unity和Pantheon用户界面，它们都使用了GNOME栈。

同样、Arc主题的开发者提醒我们它已经成功地在Ubuntu 15.04（Vivid Vervet）、 Arch Linux、 elementary OS 0.3 Freya、 Fedora 21、 Fedora 22、 Debian GNU/Linux 8.0 (Jessie)、 Debian Testing、 Debian Unstable、 openSUSE 13.2、 openSUSE Tumbleweed和Gentoo测试过了。

### 要求和安装指导 ###

要构建Arc主题，你需要先安装一些包，比如autoconf、 automake、 pkg-config (对Fedora的pkgconfig)、基于Debian/Ubuntu-based发行版的libgtk-3-dev或者基于RPM的gtk3-devel、 git、 gtk2-engines-pixbuf和gtk-engine-murrine (对Fedora的gtk-murrine-engine)。

Arc主题还没有二进制包，因此你需要从git仓库中取下最新的源码并编译。这样，打开终端并运行下面的命令，一行行地，并在每行的末尾按下回车键并等待上一步完成来继续一步。

    git clone https://github.com/horst3180/arc-theme --depth 1 && cd arc-theme
    git fetch --tags
    git checkout $(git describe --tags `git rev-list --tags --max-count=1`)
    ./autogen.sh --prefix=/usr
    sudo make install

就是这样！此时你已经在你的GNU/Linux发行版中安装了Arc主题，如果你使用GNOME可以使用GONME Tweak工具或者如果你使用Unity可以使用Unity Tweak工具来激活主题。玩得开心也不要忘了在下面的评论栏里留下你的截图。

![](http://i1-news.softpedia-static.com/images/news2/Here-s-How-to-Install-the-Beautiful-Arc-GTK-plus-Flat-Theme-on-Linux-483143-2.jpg)

![](http://i1-news.softpedia-static.com/images/news2/Here-s-How-to-Install-the-Beautiful-Arc-GTK-plus-Flat-Theme-on-Linux-483143-3.jpg)

![](http://i1-news.softpedia-static.com/images/news2/Here-s-How-to-Install-the-Beautiful-Arc-GTK-plus-Flat-Theme-on-Linux-483143-4.jpg)

--------------------------------------------------------------------------------

via: http://news.softpedia.com/news/Here-s-How-to-Install-the-Beautiful-Arc-GTK-plus-Flat-Theme-on-Linux-483143.shtml

作者：[Marius Nestor][a]
译者：[geekpi](https://github.com/geekpi)
校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创翻译，[Linux中国](https://linux.cn/) 荣誉推出

[a]:http://news.softpedia.com/editors/browse/marius-nestor
[1]:https://github.com/horst3180/Arc-theme
[2]:
[3]:
[4]:
[5]:
[6]:
[7]:
[8]:
[9]:
[10]:
[11]:
[12]:
[13]:
[14]:
[15]:
[16]:
[17]:
[18]:
[19]:
[20]: