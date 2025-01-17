
# 壹缠-缠论分析工具使用手册

![617947393](https://user-images.githubusercontent.com/2844717/144464627-e9854e0c-6aba-4274-9e86-b5035da29175.jpg)

## 功能说明

- **笔段走势** - 黄线为当前级别K线构成的笔，橙线为基于当前级别笔生成的段，紫线为基于当前级别段生成的走势
- **MACD面积** - 笔段走势的末端数字为对应笔段的MACD面积,黄色为笔MACD面积，橙色为段MACD面积，紫色为走势MACD面积
- **中枢级别** - 中枢以白色、橙色和紫色框标注，两端数字为中枢上下沿值
- **K线回放** - 快捷键说明: 空格键(开始/暂停/继续 K线回放)、左箭头 (向前回退一根K线)、右箭头(向后前进一根K线)
- **图表操作** - 支持滚轮缩放图表、鼠标拖拽移动图表
- **标的搜索** - 搜索框 可搜索全市场标的 点击返回的搜索结果切换标的 (支持按键精灵机制 全局自动捕获按键输入 响应搜索结果)
- **秒级K线** - 交易所不直接提供秒级别K线数据 所以无秒级别历史K线 依据毫秒Tick合并生成实时高精度秒级K线（需在开盘时才能使用）

## 设置说明

![image](https://user-images.githubusercontent.com/2844717/144468131-fa9701e7-8baa-4bf1-be99-0b2e3ad22a12.png)

## 自定义画线、画框、文字标注

![Snipaste_2021-12-10_23-11-44](https://user-images.githubusercontent.com/2844717/145596407-2cff9c4a-bc42-4fcf-b609-a550d0e568e1.png)

- 画线 - 点击工具栏画线图标, 鼠标移至目标起点，左键拖拽画线至目标终点即可
- 画框 - 点击工具栏画框图标, 鼠标移至目标起点，左键拖拽画框至目标终点即可
- 文字标注 - 点击工具栏文字标注图标，鼠标单击目标标注点，弹出对话框中输入标注文字即可，修改操作再次点击已标注文字即可。

已绘制自定义画线、画框、文字标注 都支持移动、起终点修改和删除

## 量化策略脚本

目前提供了四个示例脚本 可以参考示例脚本进行开发：
 
1. 示例脚本模板 (演示策略脚本生命周期和接口)
2. Boll线脚本 (通过脚本在图表上绘制Boll线)
3. 均线金叉策略脚本 (脚本在图表上绘制均线并在金叉时予以提示)
4. 日均线信号推送脚本 (演示聚宽数据源API和Webhook通知API 标的价格站上或跌破日均线时推送通知

量化策略脚本编程指南文档 见: https://github.com/neil-pan-s/twist-quant/blob/main/PROGRAM.md

![96948835](https://user-images.githubusercontent.com/2844717/144464811-bfa0a596-fc85-44df-9c6b-517b2dac754d.jpg)

## 企业微信Webhook地址

1. 电脑安装企业微信
2. 新建一个群（发起群聊）
3. 右键群 -> 添加机器人
4. 添加机器人 -> 新创建一个机器人 -> 自定义一个机器人名
5. 获取Webhook地址

详见 https://zhuanlan.zhihu.com/p/370006823?utm_source=wechat_session&utm_medium=social&s_r=0

## 快捷键

- **Tab** - 显示/隐藏 自选表和涨跌幅榜单 

![image](https://user-images.githubusercontent.com/2844717/144465470-6bbfd8ae-5453-4d60-864f-80ae9863fc8f.png)

- **F10** - 显示/隐藏 沪深、港股、美股 基本面数据 

![1183238751](https://user-images.githubusercontent.com/2844717/144464712-be8d61cc-bf05-4f41-9e41-059bef4be331.jpg)

## 浏览器

- **网站数据** - 不可清空壹缠网站数据
- **隐私设置和安全性** - 不可开启 "Cookie 及其他网站数据 - 关闭所有窗口时清除 Cookie 及网站数据"选项

![Snipaste_2021-12-10_21-05-09](https://user-images.githubusercontent.com/2844717/145578619-94eaed07-4ad9-4c09-96ab-7fc21756d5de.png)

## 壹缠客户端安装

以独立客户端方式使用壹缠服务 支持PC、平板和手机端 

安装地址 https://one-quant.com/twist/#/install
安装指引 见页面底部


