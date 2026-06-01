# Comfyui-Clean up video memory

Comfyui-Clean up video memory 是一个用于 ComfyUI 的自定义节点，提供内存清理功能以优化 ComfyUI 的运行性能。

## 功能介绍

请看节点案例教程

### 主要功能

本插件提供两个主要节点：

#### 1. 🎈VRAM-Cleanup (GPU显存清理)

可以帮助释放 GPU 显存，主要功能：
- 卸载模型 (offload_model)
- 清理显存缓存 (offload_cache)

#### 2. 🎈RAM-Cleanup (系统内存清理)

可以帮助释放系统内存，支持 Windows 和 Linux 系统：
- 清理文件缓存 (clean_file_cache)
- 清理进程内存 (clean_processes)
- 清理未使用的 DLL (clean_dlls)
- 支持多次重试 (retry_times)


## 安装方法

1. 将此仓库克隆或下载到您的 ComfyUI 自定义节点目录：
   ```
   git clone https://github.com/balu112121/Comfyui-Clean-up-video-memory
   ```
   或直接下载 ZIP 解压到 `custom_nodes` 目录

2. 安装依赖：
   ```
   pip install -r requirements.txt
   ```

3. 重启 ComfyUI

## 使用方法

1. 在节点浏览器中搜索 "南光AI/清理显存内存" 分类
2. 将 🎈VRAM-Cleanup 或 🎈RAM-Cleanup 添加到您的工作流中
3. 连接到工作流的适当位置，通常放在生成完成后

## 参数说明

### VRAM-Cleanup
- anything: 可以连接任何输入
- offload_model: 是否卸载模型
- offload_cache: 是否清理显存缓存

### RAM-Cleanup
- anything: 可以连接任何输入
- clean_file_cache: 是否清理文件缓存
- clean_processes: 是否清理进程内存
- clean_dlls: 是否清理未使用DLL
- retry_times: 重试次数 (1-10)

## 注意事项

- 内存清理可能会导致性能暂时下降，但可以防止长时间运行时的内存泄漏
- 建议在重要节点完成工作后使用此节点



## 安装方法

### 1. 下载插件

将本文件夹 `ComfyUI-Nanguang-LoadText` 放入 ComfyUI 的 `custom_nodes` 目录中。

### 南光AIGC

南光AIGC-AIGC全能方案设计解决专家 VX:nankodesign2001

粉丝福利：https://pre.runninghub.cn/?inviteCode=t7ztfeiw-填入邀请码，领1000RH币，每天登录还有100币 邀请码：t7ztfeiw

南光AIGC绘画 仙宫云新人注册网址---https://www.xiangongyun.com/register/MJAT43 新人注册仙宫云送5元代金券， 填写邀请码（输入我们的邀请码：MJAT43 ）还额外送3元代金券 完成后可以得到仙宫云8元账户余额，可以免费带你玩转5小时发高配4090 D显卡AIGC绘画。


PS软件（AI）插件
https://istarry.com.cn/?sfrom=jbEHmC
提供多种强大的AI功能，轻松提升设计效率，邀您免费体验

通过这个链接注册送1000RH币：https://pre.runninghub.cn/?inviteCode=t7ztfeiw 注册领1000RH币可以免费生成好多图片视频哦！

### 三大自媒体平台

小红书
https://www.xiaohongshu.com/user/profile/5fe63b41000000000100811d?m_source=itab

抖音
https://www.douyin.com/user/self?showTab=post

bilibili（B站）
https://space.bilibili.com/404783526


### 如果您受益于本项目，不妨请作者喝杯咖啡，您的支持是我最大的动力

<div style="display: flex; justify-content: left; gap: 20px;">
    <img src="https://github.com/balu112121/ComfyUI_NanKo_AI_Recognize/blob/main/Alipay.jpg" width="300" alt="支付宝收款码">
    <img src="https://github.com/balu112121/ComfyUI_NanKo_AI_Recognize/blob/main/WeChat.jpg" width="300" alt="微信收款码">
</div>

# 商务合作
如果您有定制工作流/节点的需求，或者想要学习插件制作的相关课程，请联系我
wechat:nankodesign2001
