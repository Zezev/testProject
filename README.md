# testProject


아무것도 없네 내가 채워줄게 -현선


# testPrj
## Prerequistic
### hostname
* master is hadoop master
* example
```
sudo -i 
echo "111.111.111.111 master" >> /etc/hosts   //여기다가 너꺼 마스터 IP주소 넣어
```

### Keyfile
* keyfile name : mykey.pem
```
$ ls 
do.sh  hive_empdept.sh  mykey.pem
```

## install
```
git clone https://github.com/Finfra/testPrj.git    //이것도 너의 git 주소
cd testPrj                                         // 이것도 너 폴더 testProject 네
scp ~/mykey.pem ./                                 //이것도 너의 key 이름
. do.sh
```

## Result
```
~
~
Time taken: 10.641 seconds, Fetched: 3 row(s)
Query ID = hadoop_20200107044953_150bf150-630e-4171-bec2-6a9664a12e27
Total jobs = 1
Launching Job 1 out of 1
Status: Running (Executing on YARN cluster with App id application_1578363143699_0010)

Map 1: 0(+1)/1   Reducer 2: 0/1   Reducer 3: 0/1
Map 1: 1/1   Reducer 2: 0/1   Reducer 3: 0/1
Map 1: 1/1   Reducer 2: 1/1   Reducer 3: 0(+1)/1
Map 1: 1/1   Reducer 2: 1/1   Reducer 3: 1/1
OK
20   2518.75
10   2916.6666666666665
Time taken: 1.127 seconds, Fetched: 2 row(s)
OK
dept
emp
Time taken: 0.018 seconds, Fetched: 2 row(s)
```

## Copy Right
2020.01 : JiYoung [BaekJiYoung] <지영 이메일 주소>
