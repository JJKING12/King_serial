# King_serial
多功能调试助手

当前版本更新为V1.2.1

v1.2.1:
 - 更新支持软件在线检测更新和下载
 - 支持按下"Enter"快捷键发送

V1.2.0:
 - 更新支持软件窗体记忆，下次打开为上次定义的窗体大小
 - 更新接收区最大同步支持2000条数据

V1.1.0：
 - 更新软件标题为楷体
 - 更新支持任意边角缩放
 - 更新切换为网络配置时，状态栏同步显示网络IP+端口

V1.0.0：
 - 支持软件置顶显示
 - 支持接收区暂停显示
 - 支持接收区打开/关闭自动滚屏
 - 接收区以不同颜色区分不同消息类型
 - 支持鼠标悬停侧边栏收缩UI
 - 接收区最大支持500条消息，大于500条会自动清空
 - 支持软件一键主题换肤
 - 支持热插拔识别串口
 - 预设常见波特率、支持手动输入自定义的任意波特率
 - 支持数据位5、6、7、8
 - 支持停止位1、1.5、2
 - 支持校验位None、Odd、Even
 - 支持流控None、Hard、Soft
 - 支持Ascii、16进制发送和Ascii、16进制接收
 - 支持发送回车换行
 - 支持发送完毕自动清空
 - 支持定时发送
 - 支持多条发送，提供10条数据发送
 - 支持勾选依次定时自动发送
 - 支持定时保存接收区数据
 - 支持波形保存为图片 
 - 支持波形数据点、范围、波特率无限制
 - 支持使用鼠标可进行缩放
 - 支持指定缩放X轴或Y轴，需要先选中该轴
 - 支持鼠标悬停波形上可显示当前数据点坐标值
 - 支持上位机修改通道名称，双击图例通道名称即可  
 - 支持上位机自定义协议（"协议配置"）  
 - 默认协议如下："A5A5ch1,ch2,1.2 2.5 5A5A"  
 - 支持极简协议，此种协议下通道名称由上位机自动分配，极简协议如下："A5A51.2 2.5 5A5A"  
 - 提供下位机C语言数据帧驱动示例代码，详见博客
 - 目前仅支持ModBus主机模式下数据读取
 - 支持多种数据读取协议（ASCII、RTU、TCP）
 - 支持多种数据读取显示格式
 - 支持读取数据的大小端转换
 - 支持数据表格横向显示及扩展
 - 支持TCP、UDP通信协议
 - 支持TCP、UDP服务端一对一、一对多发送
 - 支持TCP客户端自动重连服务端
 - 增加连接超时、连接异常等错误标识
