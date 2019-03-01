---
layout: post
title: The configuration of the work environment
---

(1)Another 01Game-下载、安装python3.7，下载、安装PyCharm编辑器，编写、运行“Hello World”程序 ，成功导入qrcode模块，但在编程过程中总出现属性错误问题,从网络上查阅的资料大都是以下形式:
                  import qrcode 
                  qr = qrcode.QRCode（
                  version = 1，
                  error_correction = qrcode.constants.ERROR_CORRECT_L，
                  box_size = 10，
                  border = 4，
                  ）
                  qr.add_data（'some data'）
                  qr.make（fit = True）
                  img = qr.make_image（）
                  img.save（'/ path / imagename.extension'）
                  但运行过程中仍有属性错误问题,正在想办法解决......