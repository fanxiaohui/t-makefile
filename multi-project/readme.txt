һ��Ŀ¼����
    ProjectName
	������ 01-lib
	��   ������ crc.so
	��   ��   ������ test
	��   ��       ������ Makefile��file��
	��   ������ md5.a
	��   ��   ������ test
	��   ��       ������ Makefile��file��
	��   ������ rsa
	��   ������ Syscall
	������ 02-com
	������ client
	��   ������ 01-lib
	��   ������ 02-com
	��   ������ Module1
	��   ��   ������ test
	��   ��       ������ Makefile��file��
	��   ������ Module2
	��   ��   ������ test
	��   ��       ������ Makefile��file��
	��   ������ Makefile��file��
	������ server
	��
	������ build.mk��file��
	������ Makefile��file��


����Ŀ¼˵��
����Ŀ¼Ϊ��Ŀ����Ŀ¼��ӵ�в�ͬ�Ľ���Ŀ¼��
01-lib: ����Ŀ¼����Ŀ¼Դ��ʹ�õ��Ĺ����⣨��ͷ*.h/*.c/*.h��
02-com: ����Ŀ¼����Ŀ¼����lib�⣩�������̼�Ľӿ��ļ�����ͷ*.h/*.c/*.h��
client��ģ��Ŀͻ���Դ��
server��ģ��ķ����Դ��


�����ֶ�����ģ��ʾ��������TOP_MODULE_DIR_NAMES����
client/Module2/test/Makefile

�ġ�update-mf.sh�ļ�
update-mf.sh�ű��ļ��ǰѵ�ǰ��makefile�ļ��滻��Ŀ¼��makefile�ļ���
ʹ��ʱ��ע�����Ḳ����Ŀ¼��makefile�ļ���


�塢build.mk�ļ�
build.mk�ļ����ݿ��Զ�����Ϊһ��makefile



