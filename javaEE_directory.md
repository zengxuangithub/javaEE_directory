#   java web Ŀ¼�ṹ
test
    
    
    | **WEB-INF**   
            | **web.xml**
            | **lib**
            | **classes**
            | tags
            | database.properties
    
    | **META-INF**
    
    
    | index.jsp //   �Զ����ļ�
    | js //   �Զ���Ŀ¼ 
    | css //   �Զ���Ŀ¼ 
    | images //   �Զ���Ŀ¼ 
    |  //�����Ը���ҵ�������ļ����ļ���
    
## ע�⣺
1. ������Ϊjava�淶�еĻ����ļ������ļ��� ����ɾ�����޸��ļ������ļ����� 
2. index.jsp js css images �Լ�WEB-INF��META-INF�ļ�������� ��Ϊ����Ŀ¼ �����Ա��ⲿ��վ�û�����



---

- WEB-INF java EE �淶�е������ļ��� ���ɸ���

- web.xml Ӧ�ó��������ļ�����servlet������Ӧ��������ú���������

- lib ���ڴ�Ÿ���JAR�ļ� �������ݿ�����JAR�ļ�

- classes servlet�Լ�����java��������ɵ�.class �ֽ����ļ�

- tags��ǩ��  ���ڴ���Զ����ǩ  ���Լ�������Ҫ�޸�����  ʹ��ʱ�Լ�����
 ������ jsp �ļ�ͷ����Ϊ��

```
<%@ taglibprefix="tags" tagdir="/WEB-INF /simpleTags" % >
```
- database.properties ���ݿ������ļ�

- index.jsp  webӦ���е�jspҳ��

- css css ��Դ�ļ���

- iamgesͼƬ��Դ�ļ���