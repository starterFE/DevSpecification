# Git commit ע�͹淶

## �ύ��ʽ��
````
<type>(<scope>): <subject>
// ��һ��
<body>
````

> ����ʹ��````git commit -v````�����ύ
> �ճ�����������һ���ύ��develop����������֧������codeReview��һ��ϲ���master��֧��

## ����:
````
fix: feat(0429�����µ�): add 'graphiteWidth' option

�ύ�ľ������
````


## ˵����
> type�����裩��scope����ѡ����subject�����裩��

> body(��ѡ)

### (1) type
* type����˵�� commit �����ֻ����ʹ������8����ʶ��
* br: �����ر����bug�ţ���������Է���bug�б��bug�޸����
* feat���¹��ܣ�feature��
* fix���޲�bug
* docs���ĵ���documentation��
* style�� ��ʽ����Ӱ��������еı䶯��
* refactor���ع����������������ܣ�Ҳ�����޸�bug�Ĵ���䶯��
* test�����Ӳ���
* chore���������̻������ߵı䶯
* revert: feat(pencil): add 'graphiteWidth' option (����֮ǰ��commit)

### (2)scope
scope����˵�� commit Ӱ��ķ�Χ���������ݲ㡢���Ʋ㡢��ͼ��ȵȣ�����Ŀ��ͬ����ͬ��

### (3)subject
subject�� commit Ŀ�ĵļ��������������50���ַ���
�Զ��ʿ�ͷ��ʹ�õ�һ�˳�����ʱ������change��������changed��changes
��һ����ĸСд
��β���Ӿ�ţ�.��

### (4)body
Body �����ǶԱ��� commit ����ϸ���������Էֳɶ��С�