# 常用Linux命令

## 查看日志
### tail
  语法: tail [-f][-c number | -n number | -m number | -b number | -k number] [file]
  tail file 显示file的最后10行内容<br>
  tail +20 file 显示file的内容从第20行至末尾<br>
  tail -f 文件名 默认动态查看指定文件的后10行内容<br>
  tail -fn 10 file 显示最后10行内容<br>
  tail -c 10 file 显示文件file的最后10个字符<br>

  lsof -i:22222 根据端口号查询pid<br>
# 常用Windows命
