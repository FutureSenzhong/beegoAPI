# ����һ��go���Եĺ��api���

## Beego

## ������Ŀ
```bash
bee api beegoAPI
```

## ������Ŀ
```bash
bee run -gendoc=true -downdoc=true

```

## ��Ŀ��ַ


http://127.0.0.1:5000/


## ��Ŀ�ĵ���ַ

http://127.0.0.1:5000/swagger/

## ��֧����
```bash
# ��ʼ����Ŀ�ֿ�
git init

# �����Ŀ�ļ�
git add .

# �����ύ
git commit -m "first commit"

# ����Զ�˷������ֿ�
git remote add origin git@github.com:FutureSenzhong/beegoAPI.git

# �ύ�ļ�����Զ�ֿ̲�
git push -u origin master

# ���ش������л���һ��������֧
git checkout -b dev_sz

# �ύ������֧����Զ�ֿ̲⿪����֧
git push -u origin dev_sz

# �鿴��֧
git branch -a

# ��֧����:
* dev_sz
  master
  remotes/origin/dev_sz
  remotes/origin/master

# �鿴���ط�֧Զ�̷�֧����״̬
git branch -vv

# ��֧����״̬����:
* dev_sz f9f9e76 [origin/dev_sz] project init
  master f9f9e76 [origin/master] project init


```
ps�����ڱ��غ�Զ�˶���������֧�ˣ�һ���ڱ���dev��֧��������ɺ�push��Զ��dev��֧��review code֮����Դ���pull request�����dev��֧�ϲ���master����֧
