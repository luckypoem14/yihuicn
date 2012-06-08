---
layout: post
title: 关于克隆别人的gh-pages网站的一个问题
category: misc
---
克隆了https://github.com/yihui/cn.git的源码到我的gh-pages: http://luckypoem14.github.com/yihuicn/,此网站是可以访问的，不过它跟原始网站http://yihui.name/cn/并不完全一样，我网站里面说的链接仍然是http://yihui.name/cn/下面的链接，不知何故？如何修正？
 Sent at 4:02 PM on Friday
 Zealic:  修改_config.yml 文件中的url部分为你网站的url： http://luckypoem14.github.com/yihuicn/
 Sent at 4:06 PM on Friday
 me:  非常感谢。现在http://luckypoem14.github.com/yihuicn/下面的链接是本站的内链了，不过网站的外观为何仍跟原始网站http://yihui.name/cn/不一样？
 Zealic:  这个就不知道了
 我还克隆了一个网站ddatsh.com/blog/为http://luckypoem14.github.com/test/，也需修改相应的_config.yml 文件中的url部分为你网站的url：
http://luckypoem14.github.com/test/
