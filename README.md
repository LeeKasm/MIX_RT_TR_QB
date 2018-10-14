# MIX_RT_TR_QB
强大的各种安装：qBittorrent+Deluge+rTorrent+Transmission+H5ai多功能一键脚本
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
         </div>
