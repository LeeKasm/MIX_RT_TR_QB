# MIX_RT_TR_QB
强大的各种安装：qBittorrent+Deluge+rTorrent+Transmission+H5ai多功能一键脚本
<div class="wrapper-md" id="post-panel">
	   <ol class="breadcrumb bg-white b-a" itemscope=""><li>
                 <a href="https://www.moerats.com/" itemprop="breadcrumb" title="" data-toggle="tooltip" data-original-title="返回首页"><i class="fontello fontello-home" aria-hidden="true"></i>&nbsp;首页</a>
             </li><li class="active">正文&nbsp;&nbsp;</li>
              <div style="float:right;">
   分享到：
   <style>
   .breadcrumb i.iconfont.icon-qzone:after {
    padding: 0 0 0 5px;
    color: #ccc;
    content: "/\00a0";
    }
    .breadcrumb i.fontello.fontello-weibo:after {
    padding: 0 5px 0 5px;
    color: #ccc;
    content: "/\00a0";
    }
   </style>
   <a href="http://sns.qzone.qq.com/cgi-bin/qzshare/cgi_qzshare_onekey?url=https://www.moerats.com/archives/676/&amp;title=qBittorrent+Deluge+rTorrent+Transmission+H5ai多功能一键脚本&amp;site=https://www.moerats.com/" itemprop="breadcrumb" target="_blank" title="" data-toggle="tooltip" data-original-title="分享到QQ空间" onclick="window.open(this.href, 'qzone-share', 'width=550,height=335');return false;"><i style="font-size:15px;" class="iconfont icon-qzone" aria-hidden="true"></i></a>
   <a href="http://service.weibo.com/share/share.php?url=https://www.moerats.com/archives/676/&amp;title=qBittorrent+Deluge+rTorrent+Transmission+H5ai多功能一键脚本" target="_blank" itemprop="breadcrumb" title="" data-toggle="tooltip" data-original-title="分享到微博" onclick="window.open(this.href, 'weibo-share', 'width=550,height=335');return false;"><i style="font-size:15px;" class="fontello fontello-weibo" aria-hidden="true"></i></a>   <a id="generateShareImg" itemprop="breadcrumb" title="" data-toggle="tooltip" data-original-title="生成分享图"><i style="font-size:13px;" class="fontello fontello-camera" aria-hidden="true"></i></a></div></ol>       <!--博客文章样式 begin with .blog-post-->
       <div id="postpage" class="blog-post">
        <article class="panel">
        <!--文章页面的头图-->
        <div class="entry-thumbnail" aria-hidden="true"><div class="item-thumb lazy" style="background-image: url(https://www.moerats.com/usr/themes/handsome/usr/img/sj/7.jpg)"></div></div>         <!--文章内容-->
         <div id="post-content" class="wrapper-lg">
          <div class="entry-content l-h-2x">
          <p><strong>说明：</strong>博主今天逛了下<code>Github</code>，发现了一个大佬写的一个脚本，很强大，这里分享一下，脚本可安装<code>qBittorrent</code>、<code>Deluge</code>、<code>rTorrent</code>、<code>Transmission</code>、<code>H5ai</code>、<code>Flood</code>、<code>Remote</code> <code>Desktop</code>、<code>wine &amp; mono</code>、<code>Flexget</code>、<code>rclone</code>、<code>BBR</code>及一些功能，如<code>ffmpeg</code>、<code>mediainfo</code>、<code>mkvtoolnix</code>、<code>eac3to</code>、<code>bluray</code>脚本、<code>mktorrent</code>，基本上该有的都有了，可能有些有人都没听说过，博主在后面会说明下。</p><div name="运行脚本" data-unique="运行脚本"></div><h2>运行脚本</h2><p><strong>Github地址：</strong><a href="https://github.com/Aniverse/inexistence" target="_blank">https://github.com/Aniverse/inexistence</a></p><p><strong>系统要求：</strong><code>Ubuntu 16.04</code>、<code>18.04</code>；<code>Debian 8</code>、<code>9</code> ；<code>Ubuntu 14.04</code>、<code>Debian 7</code>可以选择用脚本升级系统，且尽量使用纯净系统，即刚重装的系统。</p><p>运行命令：</p><pre><code class="hljs nginx"><span class="hljs-attribute">bash</span> -c <span class="hljs-string">"$(wget --no-check-certificate -qO- https://github.com/Aniverse/inexistence/raw/master/inexistence.sh)"</span>
<span class="hljs-comment">#或者</span>
wget --<span class="hljs-literal">no</span>-check-certificate -qO inexistence.sh https://github.com/Aniverse/inexistence/raw/master/inexistence.sh
bash inexistence.sh</code></pre><p>然后会出现以下选项：</p><pre><code class="hljs perl"><span class="hljs-comment">##关于选项及说明请先看文章后面，然后再进行选择</span>

<span class="hljs-comment">#是否升级系统，本选项只在Ubuntu 14.04、Debian 7中出现</span>
You are now running Ubuntu <span class="hljs-number">14.04</span>.<span class="hljs-number">5</span>, which is <span class="hljs-keyword">not</span> supported by this script

<span class="hljs-number">01</span>) Upgrade to Ubuntu <span class="hljs-number">16.04</span> (Default)
<span class="hljs-number">02</span>) Upgrade to Ubuntu <span class="hljs-number">18.04</span>
<span class="hljs-number">03</span>) Do NOT upgrade <span class="hljs-keyword">system</span> <span class="hljs-keyword">and</span> <span class="hljs-keyword">exit</span> script
Would you like to upgrade your <span class="hljs-keyword">system</span>? (Default <span class="hljs-number">01</span>): 

<span class="hljs-comment">#添加账号和密码</span>
The script needs a username
This will be your primary user. It can be an existing user <span class="hljs-keyword">or</span> a new user 
Enter username: rats
Confirm that username is rats, [Y]es <span class="hljs-keyword">or</span> [N]o? <span class="hljs-keyword">y</span>

The script needs a password, it will be used <span class="hljs-keyword">for</span> Unix <span class="hljs-keyword">and</span> WebUI 
The password must consist of characters <span class="hljs-keyword">and</span> numbers <span class="hljs-keyword">and</span> at least <span class="hljs-number">8</span> chars,
<span class="hljs-keyword">or</span> you can leave it blank to generate a random password
Enter the password: moerats
Enter the new password again: moerats

<span class="hljs-comment">#改变系统源</span>
Would you like to change sources list? [Y]es <span class="hljs-keyword">or</span> [N]o: <span class="hljs-keyword">y</span>
/etc/apt/sources.list will be replaced

<span class="hljs-number">01</span>) Use all available threads (Default)
<span class="hljs-number">02</span>) Use half of available threads
<span class="hljs-number">03</span>) Use one thread
<span class="hljs-number">04</span>) Use two threads
How many threads <span class="hljs-keyword">do</span> you want to <span class="hljs-keyword">use</span> <span class="hljs-keyword">when</span> compiling? (Default <span class="hljs-number">01</span>): 

<span class="hljs-comment">#安装时是否添加虚拟内存，本选项只在2G以下的服务器中显示</span>
Note that Your RAM is below <span class="hljs-number">1926</span>MB, memory may got exhausted <span class="hljs-keyword">when</span> compiling
Would you like to <span class="hljs-keyword">use</span> swap <span class="hljs-keyword">when</span> compiling? [Y]es <span class="hljs-keyword">or</span> [N]o: 

<span class="hljs-comment">#安装Deluge</span>
<span class="hljs-number">01</span>) Deluge <span class="hljs-number">1.3</span>.<span class="hljs-number">11</span>
<span class="hljs-number">02</span>) Deluge <span class="hljs-number">1.3</span>.<span class="hljs-number">12</span>
<span class="hljs-number">03</span>) Deluge <span class="hljs-number">1.3</span>.<span class="hljs-number">13</span>
<span class="hljs-number">04</span>) Deluge <span class="hljs-number">1.3</span>.<span class="hljs-number">14</span>
<span class="hljs-number">05</span>) Deluge <span class="hljs-number">1.3</span>.<span class="hljs-number">15</span>
<span class="hljs-number">30</span>) Select another version
<span class="hljs-number">40</span>) Deluge <span class="hljs-number">1.3</span>.<span class="hljs-number">13</span> from repo
<span class="hljs-number">99</span>) Do <span class="hljs-keyword">not</span> install Deluge
Which version of Deluge <span class="hljs-keyword">do</span> you want? (Default <span class="hljs-number">05</span>): 

<span class="hljs-comment">#安装qBittorrent</span>
<span class="hljs-number">01</span>) qBittorrent <span class="hljs-number">3.3</span>.<span class="hljs-number">7</span>
<span class="hljs-number">02</span>) qBittorrent <span class="hljs-number">3.3</span>.<span class="hljs-number">11</span>
<span class="hljs-number">03</span>) qBittorrent <span class="hljs-number">3.3</span>.<span class="hljs-number">14</span>
<span class="hljs-number">04</span>) qBittorrent <span class="hljs-number">3.3</span>.<span class="hljs-number">16</span>
<span class="hljs-number">11</span>) qBittorrent <span class="hljs-number">4.0</span>.<span class="hljs-number">2</span>
<span class="hljs-number">12</span>) qBittorrent <span class="hljs-number">4.0</span>.<span class="hljs-number">3</span>
<span class="hljs-number">13</span>) qBittorrent <span class="hljs-number">4.0</span>.<span class="hljs-number">4</span>
<span class="hljs-number">14</span>) qBittorrent <span class="hljs-number">4.1</span>.<span class="hljs-number">0</span>
<span class="hljs-number">15</span>) qBittorrent <span class="hljs-number">4.1</span>.<span class="hljs-number">1</span>
<span class="hljs-number">30</span>) Select another version
<span class="hljs-number">40</span>) qBittorrent <span class="hljs-number">3.3</span>.<span class="hljs-number">7</span> from repo
<span class="hljs-number">99</span>) Do <span class="hljs-keyword">not</span> install qBittorrent
Which version of qBittorrent <span class="hljs-keyword">do</span> you want? (Default <span class="hljs-number">13</span>): 

<span class="hljs-comment">#安装rTorrent，包括ruTorrent，nginx，ffmpeg 3.4.2，rar 5.5.0，h5ai</span>
<span class="hljs-number">14</span>) rTorrent <span class="hljs-number">0</span>.<span class="hljs-number">9.6</span> (feature-<span class="hljs-keyword">bind</span> branch on Jun <span class="hljs-number">6</span>, <span class="hljs-number">2018</span>)
<span class="hljs-number">15</span>) rTorrent <span class="hljs-number">0</span>.<span class="hljs-number">9.7</span> (with IPv6 support)
<span class="hljs-number">99</span>) Do <span class="hljs-keyword">not</span> install rTorrent
Note that Debian <span class="hljs-number">9</span> <span class="hljs-keyword">and</span> Ubuntu <span class="hljs-number">18.04</span> is only supported by rTorrent <span class="hljs-number">0</span>.<span class="hljs-number">9.6</span> <span class="hljs-keyword">and</span> later
Which version of rTorrent <span class="hljs-keyword">do</span> you want? (Default <span class="hljs-number">14</span>): 

<span class="hljs-comment">#安装flood，rTorrent的一个面板</span>
Would you like to install flood?  [Y]es <span class="hljs-keyword">or</span> [N]o: 

<span class="hljs-comment">#安装Transmission</span>
<span class="hljs-number">01</span>) Transmission <span class="hljs-number">2.77</span>
<span class="hljs-number">02</span>) Transmission <span class="hljs-number">2.82</span>
<span class="hljs-number">03</span>) Transmission <span class="hljs-number">2.84</span>
<span class="hljs-number">04</span>) Transmission <span class="hljs-number">2.92</span>
<span class="hljs-number">05</span>) Transmission <span class="hljs-number">2.93</span>
<span class="hljs-number">06</span>) Transmission <span class="hljs-number">2.94</span>
<span class="hljs-number">30</span>) Select another version
<span class="hljs-number">40</span>) Transmission <span class="hljs-number">2.92</span> from repo
<span class="hljs-number">99</span>) Do <span class="hljs-keyword">not</span> install Transmission
Which version of Transmission <span class="hljs-keyword">do</span> you want? (Default <span class="hljs-number">40</span>): 

<span class="hljs-comment">#安装VNC和X2Go</span>
<span class="hljs-number">01</span>) VNC  with xfce4
<span class="hljs-number">02</span>) X2Go with xfce4
<span class="hljs-number">99</span>) Do <span class="hljs-keyword">not</span> install remote desktop
Would you like to install remote desktop? (Default <span class="hljs-number">99</span>): 

<span class="hljs-comment">#安装wine和mono</span>
Would you like to install wine <span class="hljs-keyword">and</span> mono? [Y]es <span class="hljs-keyword">or</span> [N]o: 

<span class="hljs-comment">#安装MKVToolnix、mktorrent、eac3to、mediainfo、ffmpeg</span>
MKVToolnix, mktorrent, eac3to, mediainfo, ffmpeg ...
Would you like to install the above additional softwares? [Y]es <span class="hljs-keyword">or</span> [N]o: 

<span class="hljs-comment">#安装Flexget</span>
Would you like to install Flexget? [Y]es <span class="hljs-keyword">or</span> [N]o: 

<span class="hljs-comment">#安装rclone</span>
Would you like to install rclone? [Y]es <span class="hljs-keyword">or</span> [N]o: 

<span class="hljs-comment">#安装BBR</span>
Your kernel is newer than <span class="hljs-number">4.9</span>, but BBR is <span class="hljs-keyword">not</span> enabled
Would you like to <span class="hljs-keyword">use</span> BBR?  [Y]es <span class="hljs-keyword">or</span> [N]o: 

<span class="hljs-comment">#系统设置</span>
Would you like to <span class="hljs-keyword">do</span> some <span class="hljs-keyword">system</span> tweaks?  [Y]es <span class="hljs-keyword">or</span> [N]o: 
</code></pre><p>选择好后，会进行确认：<br><a data-fancybox="gallery" no-pjax="" data-type="image" data-caption="请输入图片描述" href="https://www.moerats.com/usr/picture/qDrth(1).png" class="light-link"><img src="https://www.moerats.com/usr/picture/qDrth(1).png" alt="请输入图片描述" title="请输入图片描述"></a><br>如果没问题，选择<code>y</code>开始安装，直到安装完成。<br><a data-fancybox="gallery" no-pjax="" data-type="image" data-caption="请输入图片描述" href="https://www.moerats.com/usr/picture/qDrth(2).png" class="light-link"><img src="https://www.moerats.com/usr/picture/qDrth(2).png" alt="请输入图片描述" title="请输入图片描述"></a></p><div name="选项说明" data-unique="选项说明"></div><h2>选项说明</h2><p>本选项说明可能不会及时更新，不过以后脚本更新的话，大都差不多，请自行选择安装。</p><p><strong>1、是否升级系统</strong><br>如果你的系统是<code>Debian 7</code>或<code>Ubuntu 14.04</code>，你可以用本脚本来升级到<code>Debian 8</code>、<code>9</code>或<code>Ubuntu 16.04</code>、<code>18.04</code>，理论上整个升级过程应该是无交互的，应该不会碰到什么问题，升级完后会直接执行重启命令，重启完后你需要再次运行脚本来完成软件的安装</p><p><strong>2、输入账号密码</strong><br>你输入的账号密码会被用于各类软件以及<code>SSH</code>的登录验证，用户名需要以字母开头，长度<code>4-16</code>位；密码最好同时包含字母和数字，长度至少8位，请记住用户名和密码。</p><p><strong>3、改变系统源</strong><br>其实大多数情况下无需换源；但某些盒子默认的源可能有点问题，所以这里干脆做成默认都换源了。</p><p><strong>4、安装时是否添加虚拟内存</strong><br>一些内存不够大的<code>VPS</code>在编译安装时可能物理内存不足，使用<code>swap</code>可以解决这个问题，实测<code>1GB</code>内存的<code>Vultr VPS</code>安装 <code>Flood</code>不开启<code>swap</code>的话会失败，开启就没问题了，目前对于物理内存小于<code>1926MB</code>的都默认启用<code>swap</code>，如果内存大于这个值那么你根本就不会看到这个选项。</p><p><strong>5、安装Deluge</strong><br>默认选项为从源码安装<code>1.3.15</code>，此外还会安装一些实用的<code>Deluge</code>第三方插件。</p><pre><code class="hljs">AutoRemovePlus是自动删种插件，支持WebUI与GtkUI。
ltconfig是一个调整libtorrent-rasterbar参数的插件，在安装完后就启用了High Performance Seed模式。
Stats、TotalTraffic、Pieces、LabelPlus、YaRSS2、NoFolder 都只能在GUI下设置，WebUI下无法显示。
Stats和TotalTraffic、Pieces分别可以实现速度曲线和流量统计、区块统计。
LabelPlus是加强版的标签管理，支持自动根据Tracker对种子限速，刷Frds可用；也只有GUI可用。
YaRSS2是用于RSS的插件；NoFolder可以让Deluge在下载种子时不生成文件夹，辅种可用。
</code></pre><p><strong>6、安装qBittorrent</strong><br><code>Debian 8</code>下安装<code>qBittorrent 4.0</code>目前还在测试阶段，隐藏选项<code>21</code>，是可以在<code>WebUI</code>下跳过校验的<code>3.3.11</code>版本，使用修改版客户端、跳过校验存在风险，后果自负。</p><p><strong>7、安装rTorrent</strong><br>这部分是调用修改的<code>rtinst</code>来安装的，默认选项为安装原版<code>0.9.4</code>。</p><pre><code class="hljs css">安装<span class="hljs-selector-tag">rTorrent</span>，<span class="hljs-selector-tag">ruTorrent</span>，<span class="hljs-selector-tag">nginx</span>，<span class="hljs-selector-tag">ffmpeg</span> 3<span class="hljs-selector-class">.4</span><span class="hljs-selector-class">.2</span>，<span class="hljs-selector-tag">rar</span> 5<span class="hljs-selector-class">.5</span><span class="hljs-selector-class">.0</span>，<span class="hljs-selector-tag">h5ai</span>目录列表程序。
0<span class="hljs-selector-class">.9</span><span class="hljs-selector-class">.2-0</span><span class="hljs-selector-class">.9</span><span class="hljs-selector-class">.4</span>支持<span class="hljs-selector-tag">IPv6</span>用的是打好补丁的版本，属于修改版客户端。
0<span class="hljs-selector-class">.9</span><span class="hljs-selector-class">.6</span>支持<span class="hljs-selector-tag">IPv6</span>用的是<span class="hljs-selector-tag">feature-bind</span>分支，原生支持<span class="hljs-selector-tag">IPv6</span>（<span class="hljs-selector-tag">Debian</span> 9 强制使用此版本）。
不修改<span class="hljs-selector-tag">SSH</span>端口，<span class="hljs-selector-tag">FTP</span>使用<span class="hljs-selector-tag">vsftpd</span>，端口号21，监听<span class="hljs-selector-tag">IPv6</span>。
设置了<span class="hljs-selector-tag">Deluge</span>、<span class="hljs-selector-tag">qBittorrent</span>、<span class="hljs-selector-tag">Transmission</span> <span class="hljs-selector-tag">WebUI</span>的反代。
<span class="hljs-selector-tag">ruTorrent</span>版本为来自<span class="hljs-selector-tag">master</span>分支的3<span class="hljs-selector-class">.8</span>版，此外还安装了如下的插件和主题。
<span class="hljs-selector-tag">club-QuickBox</span> <span class="hljs-selector-tag">MaterialDesign</span>第三方主题。
<span class="hljs-selector-tag">AutoDL-Irssi</span>（原版<span class="hljs-selector-tag">rtinst</span>自带）。
<span class="hljs-selector-tag">Filemanager</span>插件可以在<span class="hljs-selector-tag">ruTorrent</span>上管理文件、右键创建压缩包、生成<span class="hljs-selector-tag">mediainfo</span>和截图。
<span class="hljs-selector-tag">ruTorrent</span> <span class="hljs-selector-tag">Mobile</span>插件可以优化<span class="hljs-selector-tag">ruTorrent</span>在手机上的显示效果（不需要的话可以手动禁用插件）。
<span class="hljs-selector-tag">spectrogram</span>插件可以在<span class="hljs-selector-tag">ruTorrent</span>上获取音频文件的频谱。
<span class="hljs-selector-tag">Fileshare</span>插件创建有时限、可自定义密码的文件分享链接。
<span class="hljs-selector-tag">Mediastream</span>插件可以在线观看盒子的视频文件。</code></pre><p>隐藏选项<code>11-15</code> ，分别对应<code>1.3.5-1.3.9</code>版本，隐藏选项<code>21</code>，是可以跳过校验、全磁盘预分配的<code>1.3.15</code>版本，使用修改版客户端、跳过校验 存在风险，后果自负。</p><p><strong>8、安装flood</strong><br>选择不安装<code>rTorrent</code>的话这个选项不会出现，<code>Flood</code>是<code>rTorrent</code>的另一个<code>WebUI</code>，界面美观，加载速度快，不过功能上不如<code>ruTorrent</code>。</p><p><strong>9、安装Transmission</strong><br><code>Transmission</code>默认选择从仓库里安装，节省时间(<code>ban 2.93</code>以前版本的站点也不是很多），此外还会安装美化版的<code>WebUI</code>，更方便易用。隐藏选项<code>11</code>和<code>12</code>，分别对应可以跳过校验、无文件打开数限制的<code>2.92</code>、<code>2.93</code>版本，使用修改版客户端、跳过校验存在风险，后果自负。</p><p><strong>10、安装VNC和X2Go</strong><br>远程桌面选项，默认不安装，远程桌面可以完成一些<code>CLI</code>下做不了或者<code>CLI</code>实现起来很麻烦的操作，比如<code>BD-Remux</code>，<code>wine uTorrent</code>，<code>VNC</code>目前在<code>Debian</code>下安装完后无法连接，建议<code>Debian</code>系统用<code>X2Go</code>或者另外想办法安装<code>VNC</code>。</p><p><strong>11、安装wine和mono</strong><br>这两个默认也是不安装的，<code>wine</code>可以实现在<code>Linux</code>上运行<code>Windows</code>程序，比如<code>DVDFab</code>、<code>uTorrent</code>，<code>mono</code>是一个跨平台的<code>.NET</code>运行环境，<code>BDinfoCLI</code>、<code>Jackett</code>、<code>Sonarr</code>等软件的运行都需要<code>mono</code>。</p><p><strong>12、安装ffmpeg、MKVToolnix等</strong><br>安装最新版本的<code>ffmpeg</code>、<code>mediainfo</code>、<code>mkvtoolnix</code>、<code>eac3to</code>、<code>bluray</code>脚本、<code>mktorrent</code>。</p><pre><code class="hljs css"><span class="hljs-selector-tag">mediainfo</span>用最新版是因为某些站发种填信息时有这方面的要求，比如<span class="hljs-selector-tag">HDBits</span>。
<span class="hljs-selector-tag">mkvtoolnix</span>主要是用于做<span class="hljs-selector-tag">BD-Remux</span>。
<span class="hljs-selector-tag">ffmpeg</span>对于大多数盒子用户来说主要是拿来做视频截图用，采用<span class="hljs-selector-tag">git</span>的<span class="hljs-selector-tag">Static</span> <span class="hljs-selector-tag">Builds</span>。
<span class="hljs-selector-tag">eac3to</span>需要<span class="hljs-selector-tag">wine</span>来运行，做<span class="hljs-selector-tag">remux</span>时用得上。
<span class="hljs-selector-tag">mktorrent</span>由于1<span class="hljs-selector-class">.1</span>版的实际表现不是很理想，因此选择从系统源安装1<span class="hljs-selector-class">.0</span>版本。
<span class="hljs-selector-tag">BDinfoCLI</span>已经自带了，需要<span class="hljs-selector-tag">mono</span>来运行。
<span class="hljs-selector-tag">bluray</span>其实也自带了。
</code></pre><p><strong>13、安装Flexget</strong><br>默认不安装；这里启用了<code>daemon</code>模式和<code>WebUI</code>，还预设了一些模板，仅供参考，因为配置文件里的<code>passkey</code>需要用户自己修改，所以这里也没有启用<code>schedules</code>或<code>crontab</code>，需要的话自己设置</p><p><strong>14、安装rclone</strong><br>默认不安装。安装好后自己输入<code>rclone config</code>进行配置。</p><p><strong>15、安装BBR</strong><br>如果你想安装魔改版<code>BBR</code>或锐速，请移步到：<a href="https://www.moerats.com/archives/387/" target="_blank">BBR+BBR魔改+Lotsever(锐速)一键脚本</a>，脚本会检测你当前的内核版本，大于<code>4.9</code>是默认不安装新内核与<code>BBR</code>，高于<code>4.9</code>是默认直接启用<code>BBR</code>（不安装新内核）。</p><p><strong>16、系统设置</strong><br>默认启用，具体操作如下：</p><pre><code class="hljs css">修改时区为<span class="hljs-selector-tag">UTC</span>+8
语言编码设置为<span class="hljs-selector-tag">en</span><span class="hljs-selector-class">.UTF-8</span>
设置<span class="hljs-selector-tag">alias</span>简化命令
提高系统文件打开数
修改<span class="hljs-selector-tag">screen</span>设置
释放最大分区的保留空间
</code></pre><div name="增加功能" data-unique="增加功能"></div><h2>增加功能</h2><p>以下是作者准备加入的功能，对该脚本有兴趣的可以随时关注<a href="https://github.com/Aniverse/inexistence" target="_blank">Github地址</a>。</p><pre><code class="hljs shell"><span class="hljs-meta">#</span><span class="bash">Password</span>
修改SSH、Deluge、ruTorrent、Transmission、qBittorrent、Flexget密码的脚本
<span class="hljs-meta">
#</span><span class="bash">Version</span>
升级、降级Deluge、ruTorrent、Transmission、qBittorrent版本的脚本
<span class="hljs-meta">
#</span><span class="bash">Box</span>
考虑把各种客户端的安装每个都做成单独的脚本，然后在inexistence、banben中需要安装的时候直接调用，这个思路是从 QuickBox那边学到的，最后的命令大概这样子box install vnc、box purge qbittorrent。
</code></pre><hr class="content-copyright"><blockquote class="content-copyright"><p class="content-copyright">版权声明：本文为原创文章，版权归 <a href="https://www.moerats.com/" target="_blank">Rat's Blog</a> 所有，转载请注明出处！</p><p class="content-copyright">本文链接：<a class="content-copyright" href="https://www.moerats.com/archives/676/">https://www.moerats.com/archives/676/</a></p><p class="content-copyright">注意：本博客邮件回复通知已开启，评论的时候请填写正确的邮箱，虚假邮箱直接删除！</p></blockquote>          </div>
                              <!--文章页脚的广告位-->
                 搬瓦工年付<code>$18</code>的<code>7</code>机房套餐补货了，电信联通优化，<code>512M</code>内存/<code>500G</code>流量/<code>1G</code>带宽，建站稳定，优惠码：<code>BWH1ZBPVK</code>，【<a href="https://bwh1.net/aff.php?aff=16161&amp;pid=43" target="_blank"><span style="color:red">点击购买</span></a>】！
<br>
搬瓦工年付<code>$28</code>的<code>CN2</code>高速线路，<code>512M</code>内存/<code>500G</code>流量/<code>1G</code>带宽，电信联通优化，延迟低，速度快，建站稳定，优惠码同上，【<a href="https://bwh1.net/aff.php?aff=16161&amp;pid=56" target="_blank"><span style="color:red">点击购买</span></a>】！
<br>
<code>Vultr</code>最新活动，充<code>$5</code>送<code>$33</code>，可以用<code>$2.5</code>的服务器一年多，活动随时结束，快上车【<a href="https://www.moerats.com/archives/543/" target="_blank"><span style="color:red">点击查看</span></a>】！                          <!--文章的页脚部件：打赏和其他信息的输出-->
             
             <div class="show-foot">
                 <div class="notebook">
                     <i class="fontello fontello-clock-o"></i>
                     <span>最后修改：2018 年 07 月 14 日 06 : 22  AM</span>
                 </div>
                 <div class="copyright" data-toggle="tooltip" data-html="true" data-original-title="转载请联系作者获得授权，并注明转载地址"><span>© 著作权归作者所有</span>
                 </div>
             </div>
                                      <!--打赏模块-->
                 
             <div class="support-author">
                 <button data-toggle="modal" data-target="#myModal" class="btn btn-pay btn-danger btn-rounded"><i class="fontello fontello-wallet" aria-hidden="true"></i>&nbsp;赞赏</button>
                 <div class="mt20 text-center article__reward-info">
                     <span class="mr10">如果觉得我的文章对你有用，请随意赞赏</span>
                 </div>
             </div>
             <div id="myModal" class="modal fade bs-example-modal-sm" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel">
                 <div class="modal-dialog modal-sm" role="document">
                     <div class="modal-content">
                         <div class="modal-header">
                             <button type="button" class="close" data-dismiss="modal"><span aria-hidden="true">×</span><span class="sr-only">Close</span></button>
                             <h4 class="modal-title">赞赏作者</h4>
                         </div>
                         <div class="modal-body">
                             <p class="text-center article__reward"> <strong class="article__reward-text">扫一扫支付</strong> </p>
                             <div class="tab-content">
                                 <img nogallery="" aria-labelledby="alipay-tab" class="pay-img tab-pane fade in active" id="alipay_author" role="tabpanel" src="https://www.moerats.com/usr/ad/zfb.jpg">
                                 <img nogallery="" aria-labelledby="wechatpay-tab" class="pay-img tab-pane fade" id="wechatpay_author" role="tabpanel" src="https://www.moerats.com/usr/ad/wx.png">
                             </div>
                             <div class="article__reward-border mb20 mt10"></div>

                             <div class="text-center" role="tablist">
                                 <div class="pay-button" role="presentation"><button href="#alipay_author" id="alipay-tab" aria-controls="alipay_author" role="tab" data-toggle="tab" class="btn m-b-xs btn-info"><i class="iconfont icon-alipay" aria-hidden="true"></i><span>&nbsp;支付宝支付</span></button>
                                 </div>
                                 <div class="pay-button" role="presentation"><button href="#wechatpay_author" id="wechatpay-tab" aria-controls="wechatpay_author" role="tab" data-toggle="tab" class="btn m-b-xs btn-success"><i class="iconfont icon-wechatpay" aria-hidden="true"></i><span>&nbsp;微信支付</span></button>
                                 </div>
                             </div>
                         </div>
                     </div>
                 </div>
             </div>
                                  <!--/文章的页脚部件：打赏和其他信息的输出-->
         </div>
        </article>
       </div>
       <!--上一篇&下一篇-->
       <nav class="m-t-lg m-b-lg">
        <ul class="pager">
        <li class="next"> <a href="https://www.moerats.com/archives/674/" title="" data-toggle="tooltip" data-original-title="使用PHPDNS为DNSmasq搭建一个WEB界面"> 下一篇 </a></li>   <li class="previous"> <a href="https://www.moerats.com/archives/679/" title="" data-toggle="tooltip" data-original-title="Django框架开发的仿zhuye.kim的简单个人主页/导航程序，带后台"> 上一篇 </a></li>
        </ul>
       </nav>
       <!--评论-->
        
            <style>
            textarea#comment{
                background-image: url('https://www.moerats.com/usr/gn.png');
                background-color: #fafdff;
            }
        </style>
    
    
    <div id="comments">
        
        
        <!--如果允许评论，会出现评论框和个人信息的填写-->
                    <div id="respond-post-676" class="respond comment-respond">

                <h4 id="reply-title" class="comment-reply-title m-t-lg m-b">发表评论                    <small class="cancel-comment-reply">
                        <a id="cancel-comment-reply-link" href="https://www.moerats.com/archives/676/#respond-post-676" rel="nofollow" style="display:none" onclick="return TypechoComment.cancelReply();">取消回复</a>                    </small>
                </h4>
                <form id="comment_form" method="post" action="https://www.moerats.com/archives/676/comment" class="comment-form" role="form">
                    <div class="comment-form-comment form-group">
                        <label for="comment">评论                            <span class="required text-danger">*</span></label>
                        <textarea id="comment" class="textarea form-control OwO-textarea" name="text" rows="5" placeholder="说点什么吧……" onkeydown="if(event.ctrlKey&amp;&amp;event.keyCode==13){document.getElementById('submit').click();return false};"></textarea>
                        <div class="OwO">
            <div class="OwO-logo"><i class="fa fa-emo-tongue face"></i><span class="OwOlogotext">表情</span></div>
            <div class="OwO-body" style="width: 100%"><div class="OwO-title"><span>OwO</span></div>
                <ul class="OwO-items OwO-items-image OwO-items-show" style="max-height: 167px;">
                    <li class="OwO-item" title="@(呵呵)"><img src="//www.moerats.com/usr/paopao/呵呵.png"></li>
                    <li class="OwO-item" title="@(哈哈)"><img src="//www.moerats.com/usr/paopao/哈哈.png"></li>
                    <li class="OwO-item" title="@(吐舌)"><img src="//www.moerats.com/usr/paopao/吐舌.png"></li>
                    <li class="OwO-item" title="@(太开心)"><img src="//www.moerats.com/usr/paopao/太开心.png"></li>
                    <li class="OwO-item" title="@(笑眼)"><img src="//www.moerats.com/usr/paopao/笑眼.png"></li>
                    <li class="OwO-item" title="@(花心)"><img src="//www.moerats.com/usr/paopao/花心.png"></li>
                    <li class="OwO-item" title="@(小乖)"><img src="//www.moerats.com/usr/paopao/小乖.png"></li>
                    <li class="OwO-item" title="@(乖)"><img src="//www.moerats.com/usr/paopao/乖.png"></li>
                    <li class="OwO-item" title="@(捂嘴笑)"><img src="//www.moerats.com/usr/paopao/捂嘴笑.png"></li>
                    <li class="OwO-item" title="@(滑稽)"><img src="//www.moerats.com/usr/paopao/滑稽.png"></li>
                    <li class="OwO-item" title="@(你懂的)"><img src="//www.moerats.com/usr/paopao/你懂的.png"></li>
                    <li class="OwO-item" title="@(不高兴)"><img src="//www.moerats.com/usr/paopao/不高兴.png"></li>
                    <li class="OwO-item" title="@(怒)"><img src="//www.moerats.com/usr/paopao/怒.png"></li>
                    <li class="OwO-item" title="@(汗)"><img src="//www.moerats.com/usr/paopao/汗.png"></li>
                    <li class="OwO-item" title="@(黑线)"><img src="//www.moerats.com/usr/paopao/黑线.png"></li>
                    <li class="OwO-item" title="@(泪)"><img src="//www.moerats.com/usr/paopao/泪.png"></li>
                    <li class="OwO-item" title="@(真棒)"><img src="//www.moerats.com/usr/paopao/真棒.png"></li>
                    <li class="OwO-item" title="@(喷)"><img src="//www.moerats.com/usr/paopao/喷.png"></li>
                    <li class="OwO-item" title="@(惊哭)"><img src="//www.moerats.com/usr/paopao/惊哭.png"></li>
                    <li class="OwO-item" title="@(阴险)"><img src="//www.moerats.com/usr/paopao/阴险.png"></li>
                    <li class="OwO-item" title="@(鄙视)"><img src="//www.moerats.com/usr/paopao/鄙视.png"></li>
                    <li class="OwO-item" title="@(酷)"><img src="//www.moerats.com/usr/paopao/酷.png"></li>
                    <li class="OwO-item" title="@(啊)"><img src="//www.moerats.com/usr/paopao/啊.png"></li>
                    <li class="OwO-item" title="@(狂汗)"><img src="//www.moerats.com/usr/paopao/狂汗.png"></li>
                    <li class="OwO-item" title="@(what)"><img src="//www.moerats.com/usr/paopao/what.png"></li>
                    <li class="OwO-item" title="@(疑问)"><img src="//www.moerats.com/usr/paopao/疑问.png"></li>
                    <li class="OwO-item" title="@(酸爽)"><img src="//www.moerats.com/usr/paopao/酸爽.png"></li>
                    <li class="OwO-item" title="@(呀咩爹)"><img src="//www.moerats.com/usr/paopao/呀咩爹.png"></li>
                    <li class="OwO-item" title="@(委屈)"><img src="//www.moerats.com/usr/paopao/委屈.png"></li>
                    <li class="OwO-item" title="@(惊讶)"><img src="//www.moerats.com/usr/paopao/惊讶.png"></li>
                    <li class="OwO-item" title="@(睡觉)"><img src="//www.moerats.com/usr/paopao/睡觉.png"></li>
                    <li class="OwO-item" title="@(笑尿)"><img src="//www.moerats.com/usr/paopao/笑尿.png"></li>
                    <li class="OwO-item" title="@(挖鼻)"><img src="//www.moerats.com/usr/paopao/挖鼻.png"></li>
                    <li class="OwO-item" title="@(吐)"><img src="//www.moerats.com/usr/paopao/吐.png"></li>
                    <li class="OwO-item" title="@(犀利)"><img src="//www.moerats.com/usr/paopao/犀利.png"></li>
                    <li class="OwO-item" title="@(小红脸)"><img src="//www.moerats.com/usr/paopao/小红脸.png"></li>
                    <li class="OwO-item" title="@(懒得理)"><img src="//www.moerats.com/usr/paopao/懒得理.png"></li>
                    <li class="OwO-item" title="@(勉强)"><img src="//www.moerats.com/usr/paopao/勉强.png"></li>
                    <li class="OwO-item" title="@(爱心)"><img src="//www.moerats.com/usr/paopao/爱心.png"></li>
                    <li class="OwO-item" title="@(心碎)"><img src="//www.moerats.com/usr/paopao/心碎.png"></li>
                    <li class="OwO-item" title="@(玫瑰)"><img src="//www.moerats.com/usr/paopao/玫瑰.png"></li>
                    <li class="OwO-item" title="@(礼物)"><img src="//www.moerats.com/usr/paopao/礼物.png"></li>
                    <li class="OwO-item" title="@(彩虹)"><img src="//www.moerats.com/usr/paopao/彩虹.png"></li>
                    <li class="OwO-item" title="@(太阳)"><img src="//www.moerats.com/usr/paopao/太阳.png"></li>
                    <li class="OwO-item" title="@(星星月亮)"><img src="//www.moerats.com/usr/paopao/星星月亮.png"></li>
                    <li class="OwO-item" title="@(钱币)"><img src="//www.moerats.com/usr/paopao/钱币.png"></li>
                    <li class="OwO-item" title="@(茶杯)"><img src="//www.moerats.com/usr/paopao/茶杯.png"></li>
                    <li class="OwO-item" title="@(蛋糕)"><img src="//www.moerats.com/usr/paopao/蛋糕.png"></li>
                    <li class="OwO-item" title="@(大拇指)"><img src="//www.moerats.com/usr/paopao/大拇指.png"></li>
                    <li class="OwO-item" title="@(胜利)"><img src="//www.moerats.com/usr/paopao/胜利.png"></li>
                    <li class="OwO-item" title="@(OK)"><img src="//www.moerats.com/usr/paopao/OK.png"></li>
                    <li class="OwO-item" title="@(沙发)"><img src="//www.moerats.com/usr/paopao/沙发.png"></li>
                    <li class="OwO-item" title="@(手纸)"><img src="//www.moerats.com/usr/paopao/手纸.png"></li>
                    <li class="OwO-item" title="@(香蕉)"><img src="//www.moerats.com/usr/paopao/香蕉.png"></li>
                    <li class="OwO-item" title="@(便便)"><img src="//www.moerats.com/usr/paopao/便便.png"></li>
                    <li class="OwO-item" title="@(药丸)"><img src="//www.moerats.com/usr/paopao/药丸.png"></li>
                    <li class="OwO-item" title="@(红领巾)"><img src="//www.moerats.com/usr/paopao/红领巾.png"></li>
                    <li class="OwO-item" title="@(蜡烛)"><img src="//www.moerats.com/usr/paopao/蜡烛.png"></li>
                    <li class="OwO-item" title="@(音乐)"><img src="//www.moerats.com/usr/paopao/音乐.png"></li>
                    <li class="OwO-item" title="@(灯泡)"><img src="//www.moerats.com/usr/paopao/灯泡.png"></li>
                </ul>
                <ul class="OwO-items OwO-items-image" style="max-height: 167px;">
                    <li class="OwO-item" title="@(高兴)"><img src="//www.moerats.com/usr/alu/高兴.png"></li>
                    <li class="OwO-item" title="@(不高兴)"><img src="//www.moerats.com/usr/alu/不高兴.png"></li>
                    <li class="OwO-item" title="@(皱眉)"><img src="//www.moerats.com/usr/alu/皱眉.png"></li>
                    <li class="OwO-item" title="@(邪恶)"><img src="//www.moerats.com/usr/alu/邪恶.png"></li>
                    <li class="OwO-item" title="@(大囧)"><img src="//www.moerats.com/usr/alu/大囧.png"></li>
                    <li class="OwO-item" title="@(惊喜)"><img src="//www.moerats.com/usr/alu/惊喜.png"></li>
                    <li class="OwO-item" title="@(小眼睛)"><img src="//www.moerats.com/usr/alu/小眼睛.png"></li>
                    <li class="OwO-item" title="@(无语)"><img src="//www.moerats.com/usr/alu/无语.png"></li>
                    <li class="OwO-item" title="@(傻笑)"><img src="//www.moerats.com/usr/alu/傻笑.png"></li>
                    <li class="OwO-item" title="@(期待)"><img src="//www.moerats.com/usr/alu/期待.png"></li>
                    <li class="OwO-item" title="@(龇牙)"><img src="//www.moerats.com/usr/alu/龇牙.png"></li>
                    <li class="OwO-item" title="@(喜极而泣)"><img src="//www.moerats.com/usr/alu/喜极而泣.png"></li>
                    <li class="OwO-item" title="@(脸红)"><img src="//www.moerats.com/usr/alu/脸红.png"></li>
                    <li class="OwO-item" title="@(来亲亲)"><img src="//www.moerats.com/usr/alu/来亲亲.png"></li>
                    <li class="OwO-item" title="@(汗如雨下)"><img src="//www.moerats.com/usr/alu/汗如雨下.png"></li>
                    <li class="OwO-item" title="@(酷炸天)"><img src="//www.moerats.com/usr/alu/酷炸天.png"></li>
                    <li class="OwO-item" title="@(抠鼻)"><img src="//www.moerats.com/usr/alu/抠鼻.png"></li>
                    <li class="OwO-item" title="@(叼烟)"><img src="//www.moerats.com/usr/alu/叼烟.png"></li>
                    <li class="OwO-item" title="@(吐血)"><img src="//www.moerats.com/usr/alu/吐血.png"></li>
                    <li class="OwO-item" title="@(流口水)"><img src="//www.moerats.com/usr/alu/流口水.png"></li>
                    <li class="OwO-item" title="@(呕吐不止)"><img src="//www.moerats.com/usr/alu/呕吐不止.png"></li>
                    <li class="OwO-item" title="@(吐舌)"><img src="//www.moerats.com/usr/alu/吐舌.png"></li>
                    <li class="OwO-item" title="@(闭嘴)"><img src="//www.moerats.com/usr/alu/闭嘴.png"></li>
                    <li class="OwO-item" title="@(不出所料)"><img src="//www.moerats.com/usr/alu/不出所料.png"></li>
                    <li class="OwO-item" title="@(装逼)"><img src="//www.moerats.com/usr/alu/装逼.png"></li>
                    <li class="OwO-item" title="@(尴尬)"><img src="//www.moerats.com/usr/alu/尴尬.png"></li>
                    <li class="OwO-item" title="@(喷水)"><img src="//www.moerats.com/usr/alu/喷水.png"></li>
                    <li class="OwO-item" title="@(炒鸡愤怒)"><img src="//www.moerats.com/usr/alu/炒鸡愤怒.png"></li>
                    <li class="OwO-item" title="@(干得好)"><img src="//www.moerats.com/usr/alu/干得好.png"></li>
                    <li class="OwO-item" title="@(鄙视)"><img src="//www.moerats.com/usr/alu/鄙视.png"></li>
                    <li class="OwO-item" title="@(捂眼)"><img src="//www.moerats.com/usr/alu/捂眼.png"></li>
                    <li class="OwO-item" title="@(无所谓)"><img src="//www.moerats.com/usr/alu/无所谓.png"></li>
                    <li class="OwO-item" title="@(喜大普奔)"><img src="//www.moerats.com/usr/alu/喜大普奔.png"></li>
                    <li class="OwO-item" title="@(丢脸)"><img src="//www.moerats.com/usr/alu/丢脸.png"></li>
                    <li class="OwO-item" title="@(含羞)"><img src="//www.moerats.com/usr/alu/含羞.png"></li>
                    <li class="OwO-item" title="@(思考)"><img src="//www.moerats.com/usr/alu/思考.png"></li>
                    <li class="OwO-item" title="@(鼓掌)"><img src="//www.moerats.com/usr/alu/鼓掌.png"></li>
                    <li class="OwO-item" title="@(观察)"><img src="//www.moerats.com/usr/alu/观察.png"></li>
                    <li class="OwO-item" title="@(发现此事并不简单)"><img src="//www.moerats.com/usr/alu/发现此事并不简单.png"></li>
                    <li class="OwO-item" title="@(黑线)"><img src="//www.moerats.com/usr/alu/黑线.png"></li>
                    <li class="OwO-item" title="@(汗)"><img src="//www.moerats.com/usr/alu/汗.png"></li>
                    <li class="OwO-item" title="@(泪流成河)"><img src="//www.moerats.com/usr/alu/泪流成河.png"></li>
                    <li class="OwO-item" title="@(阴暗)"><img src="//www.moerats.com/usr/alu/阴暗.png"></li>
                    <li class="OwO-item" title="@(腹黑)"><img src="//www.moerats.com/usr/alu/腹黑.png"></li>
                    <li class="OwO-item" title="@(蜡烛)"><img src="//www.moerats.com/usr/alu/蜡烛.png"></li>
                    <li class="OwO-item" title="@(投降)"><img src="//www.moerats.com/usr/alu/投降.png"></li>
                    <li class="OwO-item" title="@(吐血倒地)"><img src="//www.moerats.com/usr/alu/吐血倒地.png"></li>
                    <li class="OwO-item" title="@(便便)"><img src="//www.moerats.com/usr/alu/便便.png"></li>
                    <li class="OwO-item" title="@(长草)"><img src="//www.moerats.com/usr/alu/长草.png"></li>
                    <li class="OwO-item" title="@(肿包)"><img src="//www.moerats.com/usr/alu/肿包.png"></li>
                    <li class="OwO-item" title="@(陷入深思)"><img src="//www.moerats.com/usr/alu/陷入深思.png"></li>
                    <li class="OwO-item" title="@(献花)"><img src="//www.moerats.com/usr/alu/献花.png"></li>
                    <li class="OwO-item" title="@(绿绿)"><img src="//www.moerats.com/usr/alu/绿绿.png"></li>
                    <li class="OwO-item" title="@(中枪)"><img src="//www.moerats.com/usr/alu/中枪.png"></li>
                    <li class="OwO-item" title="@(击掌)"><img src="//www.moerats.com/usr/alu/击掌.png"></li>
                    <li class="OwO-item" title="@(扇耳光)"><img src="//www.moerats.com/usr/alu/扇耳光.png"></li>
                    <li class="OwO-item" title="@(中刀)"><img src="//www.moerats.com/usr/alu/中刀.png"></li>
                </ul>
                <div class="OwO-bar">
                    <ul class="OwO-packages">
                        <li class="OwO-package-active"><span>泡泡</span></li>
                        <li><span>阿鲁</span></li>
                    </ul>
                </div>
            </div>
            </div>
                        <div class="secret_comment" id="secret_comment" data-toggle="tooltip" data-original-title="开启该功能，您的评论仅作者和评论双方可见">
                            <label class="secret_comment_label control-label">私密评论</label>
                            <div class="secret_comment_check">
                                <label class="i-switch i-switch-sm bg-dark m-b-ss m-r">
                                    <input type="checkbox" id="secret_comment_checkbox">
                                    <i></i>
                                </label>
                            </div>
                        </div>
                    </div>
                    <!--判断是否登录-->
                                                                <div id="author_info" class="row row-sm">
                                                        <div class="comment-form-author form-group col-sm-6 col-md-4">
                                <label for="author">名称                                    <span class="required text-danger">*</span></label>
                                <div>
                                                                        <img class="author-avatar" src="https://cdn.v2ex.com/gravatar/d41d8cd98f00b204e9800998ecf8427e?s=65&amp;r=G&amp;d=" nogallery="">
                                <input id="author" class="form-control" name="author" type="text" value="" maxlength="245" placeholder="姓名或昵称">
                                </div>
                            </div>

                            <div class="comment-form-email form-group col-sm-6 col-md-4">
                                <label for="email">邮箱                                    <span class="required text-danger">*</span>
                                </label>
                                <input type="text" name="mail" id="mail" class="form-control" placeholder="邮箱 (必填,将保密)" value="">
                                <input type="hidden" name="receiveMail" id="receiveMail" value="yes">
                            </div>

                            <div class="comment-form-url form-group col-sm-12 col-md-4">
                                <label for="url">地址</label>
                                <input id="url" class="form-control" name="url" type="url" value="" maxlength="200" placeholder="网站或博客"></div>
                        </div>
                                                <!--提交按钮-->
                        <div class="form-group">
                            <button type="submit" name="submit" id="submit" class="submit btn btn-success padder-lg">
                                <span class="text">发表评论</span>
                                <span class="text-active">提交中...</span>
                            </button>
                            <i class="animate-spin fontello fontello-spinner hide" id="spin"></i>
                            <input type="hidden" name="comment_post_ID" id="comment_post_ID">
                            <input type="hidden" name="comment_parent" id="comment_parent">
                        </div>
                </form>
            </div>
        
                    <!--评论列表-->
            <h4 class="comments-title m-t-lg m-b">37 条评论</h4><ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-5203" class="comment-body comment-parent comment-odd">
            <div id="div-comment-5203" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/928c178438dd32f225b786c83d92becf?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">xixi</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-08-15T15:39:39+08:00">August 15th, 2018 at 03:39 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b></b></span><span class="comment-content-true">
                            <p>为什么这个和宝塔不能共存啊装了宝塔，rutorrent网页就打不开了</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=5203#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-5203', 5203);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-5221" class="comment-body comment-child comment-level-odd comment-odd comment-by-author">
            <div id="div-comment-5221" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-08-15T19:55:53+08:00">August 15th, 2018 at 07:55 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-5203">@xixi</a></b></span><span class="comment-content-true">
                            <p>因为Web环境相冲突。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=5221#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-5221', 5221);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-5069" class="comment-body comment-parent comment-even">
            <div id="div-comment-5069" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/928c178438dd32f225b786c83d92becf?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">xixi</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-08-12T00:40:48+08:00">August 12th, 2018 at 12:40 am</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b></b></span><span class="comment-content-true">
                            <p>用了这个挂载不成功reclone 一直说挂载点不存在，求助</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=5069#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-5069', 5069);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-5085" class="comment-body comment-child comment-level-odd comment-odd comment-by-author">
            <div id="div-comment-5085" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-08-12T14:28:30+08:00">August 12th, 2018 at 02:28 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-5069">@xixi</a></b></span><span class="comment-content-true">
                            <p>这上面的挂载我没怎么用，而且你的描述也不清楚，建议你看下我博客的其它Rclone挂载教程：https://www.moerats.com/tag/rclone/。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=5085#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-5085', 5085);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-5136" class="comment-body comment-child2 comment-level-even comment-odd">
            <div id="div-comment-5136" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/928c178438dd32f225b786c83d92becf?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">xixi</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-08-13T17:28:53+08:00">August 13th, 2018 at 05:28 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-5085">@Rat's</a></b></span><span class="comment-content-true">
                            <p>自己把挂载的代码多了一个空格···所以···尴尬</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=5136#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-5136', 5136);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-5137" class="comment-body comment-child2 comment-level-odd comment-odd">
            <div id="div-comment-5137" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/928c178438dd32f225b786c83d92becf?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">xixi</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-08-13T17:29:56+08:00">August 13th, 2018 at 05:29 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-5136">@xixi</a></b></span><span class="comment-content-true">
                            <p>配合rutorrent的filemanager,直接复制到挂载盘，批量上传，神器</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=5137#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-5137', 5137);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-5146" class="comment-body comment-child2 comment-level-even comment-odd comment-by-author">
            <div id="div-comment-5146" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-08-13T21:41:09+08:00">August 13th, 2018 at 09:41 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-5137">@xixi</a></b></span><span class="comment-content-true">
                            <p>哪天研究下，给rutorrent装个filemanager插件。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=5146#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-5146', 5146);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-5162" class="comment-body comment-child2 comment-level-odd comment-even">
            <div id="div-comment-5162" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/928c178438dd32f225b786c83d92becf?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">xixi</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-08-14T10:43:53+08:00">August 14th, 2018 at 10:43 am</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-5146">@Rat's</a></b></span><span class="comment-content-true">
                            <p>这个脚本自带H5ai,挂载GD后也可以直接读取GD文件，就是只能MP4，有点蛋疼</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=5162#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-5162', 5162);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-5167" class="comment-body comment-child2 comment-level-even comment-odd comment-by-author">
            <div id="div-comment-5167" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-08-14T16:33:43+08:00">August 14th, 2018 at 04:33 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-5162">@xixi</a></b></span><span class="comment-content-true">
                            <p>记得H5ai支持格式挺多的，不仅仅mp4吧。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=5167#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-5167', 5167);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-5171" class="comment-body comment-child2 comment-level-odd comment-odd">
            <div id="div-comment-5171" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/928c178438dd32f225b786c83d92becf?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">xixi</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-08-14T16:53:08+08:00">August 14th, 2018 at 04:53 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-5167">@Rat's</a></b></span><span class="comment-content-true">
                            <p>说错，是mkv没声音</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=5171#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-5171', 5171);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-5175" class="comment-body comment-child2 comment-level-even comment-odd comment-by-author">
            <div id="div-comment-5175" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-08-14T19:00:39+08:00">August 14th, 2018 at 07:00 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-5171">@xixi</a></b></span><span class="comment-content-true">
                            <p>估计编码问题，我看过之前在H5ai上看过mkv视频。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=5175#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-5175', 5175);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-5158" class="comment-body comment-child2 comment-level-odd comment-odd">
            <div id="div-comment-5158" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/928c178438dd32f225b786c83d92becf?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">xixi</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-08-14T07:50:35+08:00">August 14th, 2018 at 07:50 am</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-5146">@Rat's</a></b></span><span class="comment-content-true">
                            <p>这个文章里面安装的就自带呢</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=5158#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-5158', 5158);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-4735" class="comment-body comment-parent comment-odd">
            <div id="div-comment-4735" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/9e94d94a38063e2f649d232efaaeda82?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">tp</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-28T16:56:54+08:00">July 28th, 2018 at 04:56 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b></b></span><span class="comment-content-true">
                            <p>请问一下下载完如何把整个文件夹取回本地啊。。h5ai不会用。。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4735#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4735', 4735);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4746" class="comment-body comment-child comment-level-odd comment-odd comment-by-author">
            <div id="div-comment-4746" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-29T10:13:29+08:00">July 29th, 2018 at 10:13 am</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4735">@tp</a></b></span><span class="comment-content-true">
                            <p>找到下载的文件夹，然后看下这个教程：https://www.moerats.com/archives/533/。你就会了。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4746#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4746', 4746);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-4730" class="comment-body comment-parent comment-even">
            <div id="div-comment-4730" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/1a93837502b52a119488083d51bebc36?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">dereshi</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-28T09:38:47+08:00">July 28th, 2018 at 09:38 am</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b></b></span><span class="comment-content-true">
                            <p>惊现星大脚本<a data-fancybox="gallery" no-pjax="" data-type="image" data-caption="" href="//www.moerats.com/usr/paopao/笑眼.png" class="light-link"><img src="//www.moerats.com/usr/paopao/笑眼.png"></a></p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4730#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4730', 4730);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-4452" class="comment-body comment-parent comment-odd">
            <div id="div-comment-4452" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/d07193f9df61ac60442e810d0710e754?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="https://www.zaera.cn" target="_blank" rel="external nofollow">ZAERA</a></b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-15T18:12:40+08:00">July 15th, 2018 at 06:12 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b></b></span><span class="comment-content-true">
                            <p>GitHub东西真不少，好东西当然要玩完啦</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4452#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4452', 4452);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4453" class="comment-body comment-child comment-level-odd comment-odd comment-by-author">
            <div id="div-comment-4453" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-15T18:35:48+08:00">July 15th, 2018 at 06:35 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4452">@ZAERA</a></b></span><span class="comment-content-true">
                            <p><a data-fancybox="gallery" no-pjax="" data-type="image" data-caption="" href="//www.moerats.com/usr/paopao/滑稽.png" class="light-link"><img src="//www.moerats.com/usr/paopao/滑稽.png"></a>是的，好东西需要挖掘。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4453#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4453', 4453);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-4445" class="comment-body comment-parent comment-even">
            <div id="div-comment-4445" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/d0012c975198e97d9745af83f69c0e9f?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="https://1years.cc/" target="_blank" rel="external nofollow">菜花</a></b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-15T13:52:09+08:00">July 15th, 2018 at 01:52 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b></b></span><span class="comment-content-true">
                            <p>星大的脚本</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4445#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4445', 4445);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4454" class="comment-body comment-child comment-level-odd comment-odd comment-by-author">
            <div id="div-comment-4454" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-15T18:36:26+08:00">July 15th, 2018 at 06:36 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4445">@菜花</a></b></span><span class="comment-content-true">
                            <p>作者在下方已经出现了。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4454#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4454', 4454);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-4428" class="comment-body comment-parent comment-odd">
            <div id="div-comment-4428" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/d1d5197b8bc445fa9f51bd8fef20cdb9?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">Wakano</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T19:30:49+08:00">July 14th, 2018 at 07:30 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b></b></span><span class="comment-content-true">
                            <p>这几天博客都登录不了为何</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4428#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4428', 4428);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4429" class="comment-body comment-child comment-level-odd comment-odd comment-by-author">
            <div id="div-comment-4429" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T20:05:17+08:00">July 14th, 2018 at 08:05 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4428">@Wakano</a></b></span><span class="comment-content-true">
                            <p>什么登录不了？是进不来？</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4429#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4429', 4429);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-4425" class="comment-body comment-parent comment-even">
            <div id="div-comment-4425" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://q.qlogo.cn/g?b=qq&amp;nk=44394810&amp;s=100" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">天文学欧诺</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T14:30:56+08:00">July 14th, 2018 at 02:30 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b></b></span><span class="comment-content-true">
                            <p>希望能支持armv7平台呀，soyoustart的小鸡如果能用这个就无敌了。谢谢</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4425#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4425', 4425);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4432" class="comment-body comment-child comment-level-odd comment-even">
            <div id="div-comment-4432" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://q.qlogo.cn/g?b=qq&amp;nk=369842286&amp;s=100" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">Aniverse</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T22:56:05+08:00">July 14th, 2018 at 10:56 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4425">@天文学欧诺</a></b></span><span class="comment-content-true">
                            <p>sys arm 可以试一下 czkwg8/QB 和 liaralabs/swizzin。我暂时没有适配 ARM 的打算（虽然好几个人找我说过了……）</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4432#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4432', 4432);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-4426" class="comment-body comment-child comment-level-odd comment-odd comment-by-author">
            <div id="div-comment-4426" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T17:05:58+08:00">July 14th, 2018 at 05:05 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4425">@天文学欧诺</a></b></span><span class="comment-content-true">
                            <p>armv7平台不能安装？或者你试试这个seedbox，https://www.moerats.com/archives/670/。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4426#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4426', 4426);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-4413" class="comment-body comment-parent comment-odd">
            <div id="div-comment-4413" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/6339519f813ea68ad2b178b5a583b4bf?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">难受啊飞</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T09:26:03+08:00">July 14th, 2018 at 09:26 am</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b></b></span><span class="comment-content-true">
                            <p>如果不希望被转播在github直接注明啊，在群里面说有什么用，真的有意思</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4413#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4413', 4413);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4431" class="comment-body comment-child comment-level-odd comment-even">
            <div id="div-comment-4431" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://q.qlogo.cn/g?b=qq&amp;nk=369842286&amp;s=100" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">Aniverse</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T22:54:03+08:00">July 14th, 2018 at 10:54 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4413">@难受啊飞</a></b></span><span class="comment-content-true">
                            <p>确实，如果不希望被人知道就不要扔在GitHub，但我又想找些经常用盒子的人来测试下，放在 GitHub 上会方便一些。<br>我以前也曾在 GitHub 的 README 上直接写了希望不要被传播，在这段话还留着的时候我只在2个 Seedbox 用户百分比很高的群里告诉过别人有这么一个辣鸡脚本，当时也基本上只有那两个群里的人知道，也都没见到群外有人提到。但后来我心态变了就删掉了这段话，所以嘛后来别人在说我也都没什么表示……现在呢应该说心情复杂吧，一方面感觉知道的人多了没啥不好，另一方面感觉自己好菜啊咋办啊 ←_←<br>不希望被宣传主要是我感觉我水平很菜吧（整个脚本都是依样画葫芦的，我其实连 git 都不会用，用 sed、awk 我经常还要百度一下用法），如果知道的人多了找我反馈问题的多了，一来我很菜我不一定能解决，二来我也没时间（但问题放着不管我又不舒服……），这样就感觉比较难受……<a data-fancybox="gallery" no-pjax="" data-type="image" data-caption="" href="//www.moerats.com/usr/paopao/委屈.png" class="light-link"><img src="//www.moerats.com/usr/paopao/委屈.png"></a></p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4431#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4431', 4431);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4440" class="comment-body comment-child2 comment-level-even comment-odd comment-by-author">
            <div id="div-comment-4440" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-15T07:48:59+08:00">July 15th, 2018 at 07:48 am</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4431">@Aniverse</a></b></span><span class="comment-content-true">
                            <p><a data-fancybox="gallery" no-pjax="" data-type="image" data-caption="" href="//www.moerats.com/usr/paopao/滑稽.png" class="light-link"><img src="//www.moerats.com/usr/paopao/滑稽.png"></a>这个脚本很不错了，能方便大家的都是好脚本，辛苦了，以后有空维护下就行了，至于问题，只要在某一个系统中能完美运行就行，其它的能解决就解决，解决不了就算了。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4440#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4440', 4440);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-4423" class="comment-body comment-child comment-level-odd comment-odd comment-by-author">
            <div id="div-comment-4423" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T12:20:50+08:00">July 14th, 2018 at 12:20 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4413">@难受啊飞</a></b></span><span class="comment-content-true">
                            <p>你回错楼层了，也许作者怕出问题吧。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4423#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4423', 4423);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-4412" class="comment-body comment-parent comment-even">
            <div id="div-comment-4412" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/6339519f813ea68ad2b178b5a583b4bf?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">难受啊飞</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T09:23:45+08:00">July 14th, 2018 at 09:23 am</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b></b></span><span class="comment-content-true">
                            <p>那为什么要放在github啊，而且之前我也就看到了，不是在搞笑吗。。。。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4412#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4412', 4412);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4422" class="comment-body comment-child comment-level-odd comment-odd comment-by-author">
            <div id="div-comment-4422" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T12:15:07+08:00">July 14th, 2018 at 12:15 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4412">@难受啊飞</a></b></span><span class="comment-content-true">
                            <p>脚本现在好像很多人知道。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4422#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4422', 4422);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-4409" class="comment-body comment-parent comment-odd">
            <div id="div-comment-4409" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://q.qlogo.cn/g?b=qq&amp;nk=720782&amp;s=100" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">anhhy</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T04:55:14+08:00">July 14th, 2018 at 04:55 am</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b></b></span><span class="comment-content-true">
                            <p>作者好像说过不希望被转载传播，在某个群里看到的说。。。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4409#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4409', 4409);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4433" class="comment-body comment-child comment-level-odd comment-even">
            <div id="div-comment-4433" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://q.qlogo.cn/g?b=qq&amp;nk=369842286&amp;s=100" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn">Aniverse</b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T22:57:48+08:00">July 14th, 2018 at 10:57 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4409">@anhhy</a></b></span><span class="comment-content-true">
                            <p>现在无所谓了……</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4433#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4433', 4433);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    
        <!--自定义评论代码结构-->

        <li id="comment-4410" class="comment-body comment-child comment-level-odd comment-odd comment-by-author">
            <div id="div-comment-4410" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T06:23:51+08:00">July 14th, 2018 at 06:23 am</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4409">@anhhy</a></b></span><span class="comment-content-true">
                            <p>哪个群？我问问，不过这是个小博客而已，没人看的。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4410#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4410', 4410);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4416" class="comment-body comment-child2 comment-level-even comment-odd">
            <div id="div-comment-4416" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/1edbec021384cea36b6eb3ad02161d28?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="https://www.wefinger.club/" target="_blank" rel="external nofollow">wefinger</a></b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T10:40:41+08:00">July 14th, 2018 at 10:40 am</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4410">@Rat's</a></b></span><span class="comment-content-true">
                            <p>小博客？黑人问号。。。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4416#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4416', 4416);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4421" class="comment-body comment-child2 comment-level-odd comment-odd comment-by-author">
            <div id="div-comment-4421" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T12:13:57+08:00">July 14th, 2018 at 12:13 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4416">@wefinger</a></b></span><span class="comment-content-true">
                            <p>对，咋了。。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4421#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4421', 4421);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4424" class="comment-body comment-child2 comment-level-even comment-odd">
            <div id="div-comment-4424" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/1edbec021384cea36b6eb3ad02161d28?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="https://www.wefinger.club/" target="_blank" rel="external nofollow">wefinger</a></b>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T13:43:29+08:00">July 14th, 2018 at 01:43 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4421">@Rat's</a></b></span><span class="comment-content-true">
                            <p>那我这种日ip小于50的岂不是。。。。。。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4424#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4424', 4424);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断开始 -->
                <div class="comment-children list-unstyled m-l-xxl">
                    <ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="comment-4427" class="comment-body comment-child2 comment-level-odd comment-odd comment-by-author">
            <div id="div-comment-4427" class="comment-body">

                <a class="pull-left thumb-sm">
                    <img nogallery="" src="https://cdn.v2ex.com/gravatar/74fb0e4834eb666f5026da78ddb089b3?s=65&amp;r=G&amp;d=" class="avatar-40 photo img-circle" style="height:40px!important; width: 40px!important;">                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="http://www.moerats.com/" target="_blank" rel="external nofollow">Rat's</a></b><label class="label bg-dark m-l-xs">博主</label>              </span>
                        <div class="comment-metadata">
                            <time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2018-07-14T17:06:20+08:00">July 14th, 2018 at 05:06 pm</time>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b><a href="#comment-4424">@wefinger</a></b></span><span class="comment-content-true">
                            <p>都差不多。</p>                        </span>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.moerats.com/archives/676/?replyTo=4427#respond-post-676" rel="nofollow" onclick="return TypechoComment.reply('comment-4427', 4427);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol> <!-- 嵌套评论所有内容-->
                </div>
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol><nav class="text-center m-t-lg m-b-lg" role="navigation"></nav>            </div>


      </div>
