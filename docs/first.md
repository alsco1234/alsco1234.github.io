_practice
## 2200080 ���ä 
- - -
### 1. git/github   
* **git** : ���� ����Ҹ� ����� ����, �ڵ� ���� �����ϴ� �۾�(**������**)   
* **git hub** : ���ÿ��� git���� �����ϴ� �ڷḦ �ٸ� ������ �����ϰų� ����ص� �� �ִ� ������Ʈ(**���� �Խ���**)   
* **git�� ������ �����ϴ� ����**   
> * untracted : init   
> * modified   
> * staged : add   
> * commited : commmit   
- - -
### 2. Alias ���� / Branch     
* **Alias** : ����, �����   
> * vi ������ �̿� (vi ~/.gitconfig)   
* **Branch** : Ŀ�Ե��� �������ϴ� ������    
> * Branch ���� : git branch "���귣ġ�̸�"   
> * Branch ���� : git checkout "�̵��Һ귣ġ�̸�"   
> * Branch Ȯ�� : git branch   
> * Branch ���� : git merge "�����Һ귣ġ�̸�" --> �귣ġ�� ������ �귣ġ�� ����   
> * Branch ���Ȯ�� : git log   
> * Ŀ�� ��� : git reset      
* **merge conflict**   
<pre>
<code>
void message(){
  puts("branch is good");
 }
 void main(){
 <<<<<<<< HEAD
  puts("branch is good");
========
  message();
 >>>>>>>> testing
}
</code>
</pre>
HEAD���� ����� �κ��� <<<HEAD���� ===����   
testing �귣ġ���� ����� �κ��� ====���� >>>testing����
- - -
### 3. markdown / PR
* **markdown** : = md����, �ؽ�Ʈ�� ����
> * ���� �������Ʈ https://gist.github.com/ihoneymon/652be052a0727ad59601  
* **Pull Request** : ������ merge�ش޶�� ��û      
* ����
> * 1.Fork
> * 2.clone, remote ����
> * 3.branch ����
> * 4.���� �۾� �� sdd, commit, push
> * 5.Pull Request ����
> * 6.�ڵ帮��, Merge Pull Request
> * 7.Merge ���� branch ���� �� ����ȭ

