˵����
1���ű�ʹ��seleniumģ����б�д��pip install selenium
2��ʹ����Ҫ�߰�װchrome��Ӧ�汾��webdriver�ںˣ�https://npm.taobao.org/mirrors/chromedriver��https://registry.npmmirror.com/binary.html?path=chromedriver/
3�����غ󽫽�ѹ�ġ�chromedriver.exe���ŵ�python��װĿ¼�£�
������У����Ը��Ĵ��룺
�ҵ�driver=webdriver.Chrome(chrome_options=chrome_options)�����ĳ�driver = webdriver.Chrome(chrome_options=chrome_options, executable_path=r'python��װĿ¼\chromedriver.exe')

ʹ�ã�
1���ڽű�ͳ��Ŀ¼����һ����ip.txt��
2�����нű�����ͬ��Ŀ¼����һ��result�ļ��У����IP��ַ�Ľ�������