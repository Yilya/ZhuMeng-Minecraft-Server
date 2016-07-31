# **DDoS 源头追踪**

## **攻击前**
- ### **7 月 30 日凌晨 01:58 - 我几乎没人来的网站有人注册了一个账号**

  ![](http://ww3.sinaimg.cn/large/a6b662bfgw1f6d9zgtopwj20cj045mx8.jpg)

  ![](http://ww4.sinaimg.cn/large/a6b662bfgw1f6da35c324j20du02eaa1.jpg)
  **留的邮箱是```a445491251@qq.com ```**

  由于我的网站开启了CDN，所以只能看到他是通过香港节点访问网站的。
  **所处距离靠近香港** 或使用了VPN

- ### **7 月 30 日凌晨 01:59 - 对方开始攻击**

  ![](http://ww1.sinaimg.cn/large/a6b662bfgw1f6da3qpwvaj20ul06r767.jpg)

  **几乎没什么防御的服务器被瞬间打死，服务商发来提醒邮件**

  那么问题来了。开启CDN后对方是怎么知道IP的？
  - 因为网站会给每个注册用户发一封邮件，**邮件中会包含服务器的真实IP地址**
  - 所以**他收到邮件获得IP后就开始攻击**

- ### **7 月 30 日凌晨 02:36 - 找到 Minecraft 服务器 IP 进行攻击**

  ![](http://ww4.sinaimg.cn/large/a6b662bfgw1f6dab9q3slj20bh03ujrg.jpg)

  **或许是没有攻击痛快吧**

  这个也很容易找，百度一下我的域名，结果应该就在前面

## **攻击后**
  总之今天凌晨两台服务器再次受到攻击导致无法访问，不能忍了。打算抓出来。

  - ### **线索**
    - **邮箱**
      ```a445491251@qq.com ```

      上 **Google** 搜一下，**信息量超大**，我们一个个看
    - **该邮箱注册的域名**

        ```mypcqq.cc```

        二话不说，直接上 **whois 查询**

        ![](http://ww1.sinaimg.cn/large/a6b662bfgw1f6damksw9xj219h0qbwk8.jpg)

        隐私保护得还挺好，不过…别急，继续往下看。

        ![](http://ww3.sinaimg.cn/large/a6b662bfgw1f6darr3r67j20ia05wab4.jpg)

        **注册城市** **海南省** 如果没有故意捏造的话。

        ![](http://ww2.sinaimg.cn/large/a6b662bfgw1f6dasxsuvqj20eg03t0sw.jpg)

        **姓名** **Xu Shanyu** 咦，所以到底叫徐善于还是许山芋呢……

        打开网站一看，是个 **QQ 机器人** 网站，而且网站**已备案**。

        ![](http://ww3.sinaimg.cn/large/a6b662bfgw1f6db4elggwj20b201xglk.jpg)

        上**工信部备案查询**。

        ![](http://ww1.sinaimg.cn/large/a6b662bfgw1f6db4ylnzpj21kw0gwwlg.jpg)

        ![](http://ww1.sinaimg.cn/large/a6b662bfgw1f6db6rwkqyj21kw0ikn2q.jpg)

        **嗯...里面十几个网站**种类繁多，还有**赌博**网站。

        攻击者应该是找的**代备案**，网站挂在这个彭家煌的名下。

        继续在他网站上搜集信息。

        ![](http://ww3.sinaimg.cn/large/a6b662bfgw1f6dbcu99vij212o0viwk5.jpg)

        **获得信息：攻击者用手机免流**

    - **红旅动漫论坛**

      ![](http://ww2.sinaimg.cn/large/a6b662bfgw1f6dbtbygcqj20dn0f9tao.jpg)

    - **疑似利益相关站点** 也是QQ机器人

      http://cocoqq.cn/

    - **耳机论坛**
      ![](http://ww3.sinaimg.cn/large/a6b662bfgw1f6dc32jkgtj20te0ahabv.jpg)

      **继续增强资料可信度** **攻击者位于海南**
