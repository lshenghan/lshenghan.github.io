Memo-> index
          ->list 
          ->add     ->add_stuMemo (备注php->json_encode->js中直接用) ->toAddStuMemo ->handleMemo("add")
          ->search


js:
Array: 
  var person = ["John", "Doe", 46];
Object:
  var person = {firstName:"John", lastName:"Doe", age:46};
  var person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};

1. Q:What is the Command Line used for?
Now that we've discussed what an interface is, and how the command line is an interface all on its own, let's look at what the command line is typically used for.

The most common use of the command line is what's called "system administration" or, basically, managing computers and servers. This includes installing and configuring software, monitoring computer resources, setting up web servers, and automating processes. The following is a list of common tasks for programmers:

Restart servers
Rename hundreds or thousands of files according to a prescribed pattern
Manage system logs
Set up scheduled tasks (cron jobs)
Debug server issues
Monkey patch code on a server
Query data
Set up databases and servers

2. Q:How to add user?
  $ useradd -g users longin_name
  $ passwd
  ----设置可使用sudo：（http://linux.vbird.org/linux_basic/0410accountmanager.php）




SELECT stu_number,grade,stu_name,if_sign,creat_date FROM jxt_memo WHERE schoolId=1 AND YEAR(creat_date)='2018' AND MONTH(creat_date)='9';