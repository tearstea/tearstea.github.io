
<img src="/PigSec/sec.jpg" width="800">


## 前言

  为了拥有个人专属网站，在不断寻觅之中找到了一个模板，然后按照对方的教程在这其中磕磕碰碰终于把个人博客给搭建成功了，首先感谢[qiubaiying](https://github.com/qiubaiying/qiubaiying.github.io)的模板与指导，当然也通过他了解了[Hux](https://github.com/Huxpro/huxpro.github.io)的建站经历，感谢他们。如果想了解更详细的建站过程可以戳这[《利用 GitHub Pages 快速搭建个人博客》](http://www.jianshu.com/p/e68fba58f75c) 或 [wiki](https://github.com/qiubaiying/qiubaiying.github.io/wiki/%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B)。
  如果想了解我的博客，可以戳[这里](http ://cometogo.club/)。

  由于在建站过程中遇到了很多坑，也寻找了各种各样的方法，按照前人的教程，可能我个人能力有限，总也不能建站成功，于是，我修改一些过程，最终爬坑成功了，高兴至极。此方法可能对于更多的职场小白来说更简单些。下面我把我个人的方法总结与前人之异同总结出来。希望能给想建造个人博客的人有些帮助。

## 第一步

  注册<a href="https://github.com" target="_blank">GitHub</a>个人账户并登录，可点击<a href="https://github.com" target="_blank">GitHub Pages</a>进行注册，整个界面如下。如果个人英语水平不好，可以点击右键，选择翻译成中文。
<img src="/PigSec/sec1.jpg" width="500">

## 第二步

  新建个人仓库，仓库名为：github账户名.github.io。譬如我之前建的仓库名为：tearstea.github.io。如下图所示。切记，仓库名一定要注意，必须以这样的格式，否则不成功。因为我已经建过了这个仓库，所以给了个大大的红色叹号！因为之后我们的博客用的是GitHub Pagas 在美国的免费服务器，因为便宜，你值得拥有。
<img src="/PigSec/sec2.png" width="500">

## 第三步

  点击进入下载<a href="https://desktop.github.com/" target="_blank">github desktop</a>界面并下载安装，安装之后的界面如下，用户名一定要跟你的gihub的用户名密码一样哟。
<img src="/PigSec/sec3.jpg" width="500">

## 第四步

  克隆仓库，在自己某个电脑盘里新建文件夹，我的是在自己的E盘里新建了MyBlog文件夹，然后利用github desktop克隆之前在gihub上已经建好的仓库。点击File目录下的Clone repository或者直接用快捷键Ctrl+shift+O调出如下界面。注意用URL的界面。URL:https://github.com/tearstea/tearstea.github.io.git。URL为之间新建的仓库的网络地址，可点击tearstea.github.io这个仓库，进入之后可看到绿色的“CLONE OR DOWNLOD”,点击就可以看到URL地址了。
<img src="/PigSec/sec5.jpg" width="500">

## 第五步

  在自己的gihub界面内搜索我的tearstea.github.io，或者搜索我之前用的模板qiubaiying.github.io，会进入这样的界面。如下图。直接点击“CLONE OR DOWNLOD”，然后再点击“DOWNLOD ZIP”直接下载到哪个地方都可以，然后进行解压。
<img src="/PigSec/sec4.jpg" width="500">

## 第六步

  在刚解压好的文件下如下图，Ctrl+A全选，复制所有内容到自己之前在MyBlog文件夹已经clone好的tearstea.github.io这个文件夹。切记，不要乱复制。
<img src="/PigSec/sec6.png" width="500">

  对了，忘了一件大事，忘了给别人送个star了，等我一下，也希望你也能给我个star。star在哪儿送，在这里，请看图，红色箭头所点就是。
<img src="/PigSec/sec7.jpg" width="500">

## 第七步

>  1.注册域名
      当然可能你已经有域名了。当然，对于大部分人来说，都是第一次有自己的专属网站，那怎么注册域名呢，大家可以用阿里云或者腾讯云，我用的是腾讯云，因为是第一次注册域名，可以有优惠哟，一块钱就可以买一个自己的专属域名哟，当然也只是第一年只有一块钱，第二年就不是这个数了，这也是为什么我说用一块钱就可以建一个网站了。当然，如果不想要了，一年之后可以注销掉，在这一年中，我们就只花一块钱，其他再也不用花钱了，体验一番也是可以的，当然说不定你的域名可能在这一年中还升值了，可能有人出高价来买你的域名，你岂不是赚了，可能那个时候，你就不想卖，还想继续留着呢。
<img src="/PigSec/sec8.jpg" width="500">

>  2.域名解析
      域名注册好了之后，然后进行解析，点击解析按钮尽心解析。添加博客的IP地址：151.101.100.133，这个IP地址是 GitHub Pagas 在美国的服务器的地址 151.101.100.133,甚至你在网上搜一个github的服务器IP也可以的。或者如果你有gitbash的话，可以直接找到自己的IP地址，但相差不多，一般都不会有多大变化，都是github的服务器，都是可以用的，甚至你也可以用我的。如何查找自己的IP地址如下图,在gitbash中输入命令：ping 你的github名字.github.io按enter键即可显示出自己的github的IP地址。如下185.199.110.153即为我自己的IP地址
<img src="/PigSec/secname.jpg" width="500">

>  3.添加解析之后有两个A 记录类型,
      一个主机记录为 www,代表可以解析www.cometogo.club的域名。细心的你会发现在浏览器输入www.cometogo.club或者直接点击<a href="https://www.cometogo.club" target="_blank">这里</a>，将会直接跳转d到我个人网站主页。
      另一个为 @, 代表 cometogo.club，当然你也可以直接在浏览器中输入，也可以进入我个人网站主页。
<img src="/PigSec/sec9.png" width="500">

## 第八步

  修改tearstea.github.io文件夹下的CNAME文件，用记事本打开，当然你也可以用其他编辑器，由于个人爱好，我自己用的VS Code编辑器，大家不妨也下载一个，因为后续要用到。这个文件下只有一行文字，那就是已经解析过的域名，然后进行修改，换成我们自己的。将自己已经解析的域名替换掉之前的域名。譬如我用我自己的cometogo.club替换掉了之前的qiubaiying.top。
<img src="/PigSec/sec10.png" width="500">

## 第九步

  把自己的代码上传到自己的github，打开github desktop软件，大家会看到这样的界面。按照如下步骤就行。
  - 1 修改（内容随便写，只要自己知道就行）
  - 2 点击提交
  - 3 点击上传
<img src="/PigSec/sec11.jpg" width="500">

  上传成功之后，在浏览器里输入自己的域名www.cometogo.club，就会进入一个模板网站，诸如我的或者别人的，给大家一个别人的，因为自己的里面都修改了，不是自己的内容几乎都删完了。
<img src="/PigSec/sec12.jpg" width="500">

## 第十步

   到这一步几乎个人网站差不多已经搭建好了，接下来就是修改东西了。
 - 1.修改——config.yml文件，用自己喜欢的编辑器打开，然后进行修改，大家可以参照我的和别人的尽心再次修改，直到成为自己专属的。
<img src="/PigSec/sec13.jpg" width="500">
<img src="/PigSec/sec14.jpg" width="500">
<img src="/PigSec/sec15.png" width="500">
<img src="/PigSec/sec16.jpg" width="500">

 - 2.修改404html,about.html,index.html,offline.html,tags.html以及packag.json等内容的。具体如何修改我也就不说了，可以仿照上面的内容。修改的时候，不要一口气吃个大胖子，每次少修改点，然后再提交，上传，再刷新自己的网站。
<img src="/PigSec/sec17.jpg" width="500">
<img src="/PigSec/sec18.jpg" width="500">

 - 3.删掉不是自己的图片以及_posts文件下的博客内容。删文件的时候一定要小心了，千万不要一下子全删了，可以删一点，提交上传之  后，刷新自己的网站，看看有没有什么问题再继续删，稍微一个不慎，就可能删出了问题。少删点还能很容易撤回。在每次上传提交之后，刷新自己的网站之前，要清除一下浏览器缓存，这样才能更新到最新内容。缓存是有影响的，切记切记。当然了，提醒下子，未来我们写的博客都放在_posts文件下，不要问我为什么，编程是很严谨的语言，稍有不神，就可能崩溃，这也体现了我们的细心与专业。然后img文件夹放图片。当然对于编程语言很熟悉的可以乱折腾，至于第一次的，就不要瞎折腾了，我嘛，因为之前乱折腾，所以爬了很多坑才走出来。如果成功，

> 电脑上是这样子的：
<img src="/PigSec/sec19.png" width="500">

> 手机上是这样子的：
<img src="/PigSec/sec20.jpg" width="500">

我相信大家已经发现了，原来这是自适应的啊，不论是手机还是电脑，浏览起来毫无违和感啊。

 - 4.如果你已经有一定的编程能力了，可以在这个基础进行深层次的开发。可以利用<a href="">Ruby+DevKit+jekyll</a>，具体如何应用可以参考<a href="http://jekyllcn.com/" target="_blank">jekyll文档</a>进行再次改造。如想了解更多可扫码关注我微信公众号：互联网遗址。
<img src="/img/wechat-gongzhong.jpg">

### 备注：

  其实我之前用的gitbash命令行工具clone仓库，也可以不用github desktop，但是这对于新手来说比较麻烦，所以我选择了最简单的方式。當然了，也可以直接fork別人的模板到自己的的github倉庫裏，然後再克隆到本地。然後在進行修改。切記，每次修改的時候一定要注意力額，不然，可能出現進站不成功的情況。
  
  现在我的博客新地址迁移到这里<a href="https://gittab.cn/" target="_blank">GitTab</a>,之前的cometogo给了我女朋友，她的地址在这里<a href="https://www.cometogo.club/" target="_blank">BinGo姐</a>。

## 鸣谢

  这个模板是从这里 [qiubaiying](https://github.com/qiubaiying/qiubaiying.github.io) fork 的, 感谢这个作者。也感謝之前的作者。 其他方式可看這裏[《利用 GitHub Pages 快速搭建个人博客》](http://www.jianshu.com/p/e68fba58f75c)