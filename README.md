# swap.sh
Linux VPS一键添加/删除Swap虚拟内存

说明：很多人的VPS服务器由于内存太小，会导致很多进程被杀掉，这时候就需要我们添加Swap虚拟内存了，这里就整了个一键脚本方便懒人或小白使用。

脚本
提示：脚本不支持OpenVZ架构，安装会自动退出。

运行命令：

wget https://raw.githubusercontent.com/niaoda/swap/main/swap.sh && bash swap.sh

<img nogallery="" src="https://testingcf.jsdelivr.net/gh/Mark-1215/CDN/uploads/content/Swap.png">

然后根据选项进行操作，记得添加swap的时候填写纯数字，默认单位为M。

注意：输入分区大小时，单位为 M, 如需 1G, 直接输入 1024 即可

最后输入 free -m 检查是否添加成功
