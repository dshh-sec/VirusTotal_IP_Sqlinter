说明：
1、脚本使用selenium模块进行编写，pip install selenium
2、使用需要线安装chrome对应版本的webdriver内核，https://npm.taobao.org/mirrors/chromedriver、https://registry.npmmirror.com/binary.html?path=chromedriver/
3、下载后将解压的“chromedriver.exe”放到python安装目录下，
如果不行，可以更改代码：
找到driver=webdriver.Chrome(chrome_options=chrome_options)，更改成driver = webdriver.Chrome(chrome_options=chrome_options, executable_path=r'python安装目录\chromedriver.exe')

使用：
1、在脚本统计目录创建一个“ip.txt”
2、运行脚本会在同级目录生成一个result文件夹，存放IP地址的解析域名