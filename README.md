# ת���������ĵ�

## �����ӿ�
```
bool Start(char*ip = 0, int port = 12345);
virtual bool validate(uint32_t uid1, uint32_t sessionId, uint32_t uid2, std::string *url);
void Close();;
```
##��ȫ��֤����
Ĭ�ϲ���http get����ص�����ͨ������CRelayServer��override�麯��ʹ���Լ�����֤����

��½ת��������ʱ��
    ����Ϊurl?uid=xxx&sessionId=xxx

��ѯ�Ƿ���ת��Ȩ��ʱ��
    ����Ϊurl?uid1=xxx&sessionId=xxx&&uid2=xxx

##�����ļ���ʽ

