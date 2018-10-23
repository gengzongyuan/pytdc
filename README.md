
dc = DataCreate()
# 生成imei
# print(dc.getImei())
# 生成idfa
# print(dc.getIdfa())
# 生成手机号码
# print(dc.getPhone())
# 生成身份证信息
# print(dc.getIdCard())
# 生成图片素材，可以指定宽高
# dc.createImage(file_name='500_600素材',file_path='D:\it\pythondemo\pytdc\lib\image',width=500,height=600)
# 批量写入信息，imei,idfa,phone,idcard
dc.writeToFile(10000,'idfa',isMd5=True)
