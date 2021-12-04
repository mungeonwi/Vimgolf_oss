# Vimgolf_oss
Vimgolf_oss

### VimGolf ###

### 1 **vimgolf - 1** ###

* Add quotes to ansible playbook

* $vimgolf put 5f0f5fbe280fbf000c233304

* 최고점 : 8
----------------------------------------------------
![image](https://user-images.githubusercontent.com/87855218/144703062-6228187c-2d7c-4828-83e3-f818eb169ea1.png)
![image](https://user-images.githubusercontent.com/87855218/144703068-7f81eeeb-e72c-4fa1-94af-f91c8c094676.png)
-----------------------------------------------------
* 풀이 과정 

![vimgolf_1](https://user-images.githubusercontent.com/87855218/144703128-48da5652-7e54-4839-a3bf-7be0f605f242.gif)

score : 6

keystrokes : GWi"<END>"ZZ
  
파일의 마지막 줄로 이동 -> 현재 위치에서 입력 모드 시작 -> 현재 위치에서 입력 모드 시작 -> " 입력 ->End키(맨 뒤로)-> " 입력


---------------------------------------------------------
  
### 2 **vimgolf - 2** ###
  
*  simple replacements

* $ vimgolf put 603ba26a01b4d00009c10a49

* 최고점 : 19
  
---------------------------------------------------------
![image](https://user-images.githubusercontent.com/87855218/144703289-5481b6f5-af4f-40a7-b7bb-70da584cd1b6.png)
![image](https://user-images.githubusercontent.com/87855218/144703293-873200dd-5a1c-449a-abaf-290a4eb7a901.png)
--------------------------------------------------------------
* 풀이과정

![vimgolf_2](https://user-images.githubusercontent.com/87855218/144703307-1ea61960-1647-450a-802d-4e56d99d57e2.gif)

score : 28 

keystrokes : (Esc):%s/sublime|emacs/vim/gZZ

sublime 과 emacs 를 vim으로 치환한다.

-------------------------------------------------------------

### 3 **vimgolf - 3** ###
  
* Satisfy the go linter

* $ vimgolf put 5f1063aa8361810006e73210

* 최고점 : 20
  
------------------------------------------------------------
![image](https://user-images.githubusercontent.com/87855218/144703430-d144f328-c494-4c84-a942-c1b2e2ee9c22.png)
![image](https://user-images.githubusercontent.com/87855218/144703433-0eff6ce7-fa15-4be3-a2a2-713386d774ad.png)

------------------------------------------------------------
* 풀이과정
  
![vimgolf_3](https://user-images.githubusercontent.com/87855218/144703455-d44ceadb-74ea-4ce9-b3af-bfb848c4f989.gif)

score : 34 

keystrokes : :4<CR>ywO// <C-N> TODO<Esc>:6<CR>ywO// <C-N> TODO<Esc>ZZ

4번째 줄 이동 -> 단어 저장-> 현재 라인을 다음 줄로 밀고 입력 -> // 입력 -> 저장한 단어 붙여넣기 -> TODO입력 -> 6번째 줄로 이동 -> 단어 저장 -> 현재 라인을 다음 줄로 밀고 입력 -> //입력 -> 저장한 단어 붙여넣기 -> TODO 입력 -> ZZ 저장하고 나가기
  
---------------------------------------------------------

### 4 **vimgolf - 4** ###
  
* Plotting some variables in python

* $ vimgolf put 9v0060da5177000000000209

* 최고점 : 34
  
--------------------------------------------------------
![image](https://user-images.githubusercontent.com/87855218/144703579-a6af7912-c2e1-4e3e-98aa-0d77e5880364.png)
![image](https://user-images.githubusercontent.com/87855218/144703581-1ebbeaa6-98a3-4b76-b513-d45058193a9b.png)

------------------------------------------------------------
* 풀이 과정
  
![vimgolf_4](https://user-images.githubusercontent.com/87855218/144703650-fd84e05f-c1d6-4daa-befc-866326d029f2.gif)

  
score : 73 

keystrokes : :%s/y1/abs(y1)/g<CR>:3s/k/b<CR>:4s/k/r<CR>:5s/k/g<CR>:3s/1/2/g<CR>:4s/1/3/g<CR>:5s/1/4/g<CR>ZZ

-----------------------------------------------------------
### 5 **vimgolf - 5** ###
  
* Python dataclasses

*  $ vimgolf put 6013804df3308e0009368f1c

* 최고점 : 19
  
-----------------------------------------------------------
 
![image](https://user-images.githubusercontent.com/87855218/144703724-11240865-834c-48be-a6f4-7978803eb6a1.png)
![image](https://user-images.githubusercontent.com/87855218/144703733-15f4d9f6-c8ad-4e32-9dc9-83dd979292ba.png)

-----------------------------------------------------------
* 풀이 과정 
  
![vimgolf_5](https://user-images.githubusercontent.com/87855218/144703754-7251fb4a-234c-4c3d-beaa-ba204cb12b6e.gif)


score : 53 

keystrokes : :5<CR>yw10G$Pa,<Esc>:6<CR>yw10G$Pa,<Esc>:7<CR>yw10G$Pa,:<BS><Esc>:8<CR>yw10G$PZZ
