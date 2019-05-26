<p align="center"><img width="15%" src="icons/icon-128.png" /></p>
<h1 align="center">谷歌访问助手</h1>

最简单易用的谷歌访问助手,为chrome扩展用户量身打造。可以解决chrome扩展无法自动更新的问题，同时可以访问谷歌google搜索，gmail邮箱，google+等谷歌服务。

<table align="center">
  <tr>
    <td align="center"><img src="img/google.png" /></td>
    <td align="center"><img src="img/chrome.png" /></td>
    <td align="center"><img src="img/gmail.png" /></td>
    <td align="center"><img src="img/googleplus.png" /></td>
  </tr>
  <tr>
    <td align="center">Google搜索</td>
    <td align="center">Chrome商店</td>
    <td align="center">Gmail邮箱</td>
    <td align="center">Google+</td>
  </tr>
</table>

**本软件已破解，可永久免费使用！**

## 安装说明
打开Chrome扩展程序管理器 `chrome://extensions`
1. 勾选`开发者模式`
2. 点击`加载已解压的扩展程序`，选择本扩展所在目录（解压后的文件夹）

## 破解说明

- 本软件为破解版（By [IDforHYIT](https://idforhyit.github.io/)），已为您永久免费激活！DM团队内部使用，请勿分享！！！

- 该插件的核心代码为[bg.js](bg.js)。该文件已做代码混淆和压缩，本破解版已对该文件进行格式化。

- 该插件在Chrome启动时会检测打开的标签页是否包含推广网站，以此判断用户是否将推广网站设置为首页。因此，只需在检测标签页网址的代码上强行加入推广网站的地址，即可让该插件认为已将其添加为首页，不受12小时试用时间的限制。

  ```javascript
  a.links.push("http://360.hao245.com");
  a.links.push("http://123.hao245.com");
  ```

- 该插件通过代理服务器访问Google，代理服务器的地址和密码以及PAC脚本均由插件动态获取。研究发现，即使将PAC脚本替换掉，依然只能访问Google和GMail，其余网站无法打开，表明服务器端已进行了限制。

## 可访问的网站
            
- Google搜索  https://www.google.com/
- Chrome商店  https://chrome.google.com/webstore/category/extensions 
- Gmail邮箱   https://mail.google.com/
- ~~Google+~~（已停止个人用户服务）     https://plus.google.com/

