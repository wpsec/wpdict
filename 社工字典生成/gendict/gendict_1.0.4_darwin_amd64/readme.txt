# 对控股公司、子公司列表进行字典生成
./gendict -org test.txt

# 对已知员工列表进行字典生成,指定输出到 /tmp/out.txt 中
./gendict -name test.txt -nameout /tmp/out.txt

# 提供一个已知用户名列表
./gendict -list username.txt

# 提供一个已知用户名列表,使用自定义后缀列表
./gendict -list username.txt -suffix passuffix.txt
