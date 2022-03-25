# 每天进步1/1000

1. 今天特地找到一个用 IDEA 编程的快捷键 *CTRL SHIFT +/-*
可快速收起/展开类中的所有函数。彻底告别通过鼠标滚轮去找目标函数原始方法了。
2. Postman 的Runner 里可以执行重复的请求，比如要抽奖1000次，通过一个个手动执行，不得腱鞘炎才怪。哈哈，Postman这个工具应该还有一些值得挖掘的技巧。先留着吧
3. [IDEA使用技巧：下划线转驼峰及大小写转换插件和快捷键](https://blog.csdn.net/ZYC88888/article/details/87876390)  *shift + alt +  U*
4. IDEA 使用技巧：像缩放网页一样
5. [关于信息的获取](https://www.bilibili.com/video/BV11i4y1P7sz?share_source=copy_web) by 阿里孤尽：需要的时候准确地唤起
6. [idea工具栏如何切换到左边](https://blog.csdn.net/qq_42567791/article/details/106301502) 缩短了run 按钮点击时间,ShortKeys：control + R
7. idea 的快捷键：
    
    ```sql
    sout = System.out.println(); 
    ```
    
8. [解决git pull/push每次都需要输入密码问题](https://blog.csdn.net/nongweiyilady/article/details/77772602)
9. IDEA 上下移动 *Shift + Alt  ^* 
10. Javadoc 快捷键 alter + M
11. IDEA 清除无用 import 快捷键以及自动清除设置 *Ctrl + Alt + O*  
12. 可以通过 wiki 文档中的 mock 请求到接口返回参数（测试环境未部署时可临时用）
13. IDEA Recently files    【*command + E*】
14. 想法设法降低 bug 数量
    1. 反复检查自己的代码逻辑
    2. 测试时要考虑边界值情况
    3. 想发设法提高个人效能
    4. 顺利交作业才能给自己腾出时间来学习
15. 尽量避免被聊天打断
16. 遇到新技术，先通读文档，等用到具体技术点再细看
17. java 日期比较

```java
Date now = DateUtil.getDate();

list.removeIf(item -> now.before(item.getStartTime()) || now.after(item.getEndTime()));
替换
list.removeIf(item -> now.compareTo(item.getStartTime()) < 0 || now.compareTo(item.getEndTime()) > 0);
```

1. IDEA 完全退出项目
    1. 需要把 .idea .iml 文件都删除才行
    2. 删除后重新导入项目，并在 module 中设置好 resource
2. Chrome 可以在地址栏通过标签备注，直接检索到网址
3. MySQL insert 省略自增 ID
    
    ```sql
    INSERT INTO `sys_config`
    VALUES (null, '商城运费规则', 'sys.shop_express_rule',
            '{\"achieveAmountFreeExpress\":2000.00,\"baseCount\":2,\"baseFee\":6.00,\"extraFee\":1.00}', 'Y', 'admin',
            '2022-02-18 17:24:55', 'admin', '2022-02-22 16:25:43',
            '(每项必填)\nachieveAmountFreeExpress:满多少免运费\nbaseCount:2 几件商品内基础运费\nbaseFee:6.00 基础运费\nextraFee:1.00 超出基础运费后每件加多少');
    ```
    
4. [chorme 多开账号 导入书签](https://www.hellotech.com/guide/for/how-to-export-save-import-bookmarks-in-chrome)
5. 程序开发清单
    1. 是否兼容已有业务和数据
    2. 是否对活动开始结束时间做了限制
    3. 辅助脚本是否会带来脏数据
