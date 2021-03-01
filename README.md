# React Educational Program Winter 2021 (Accelerated Path)

**欢迎来到Triple C Educational Program Winter 2021!**  
**在项目开始之前，相信你已经非常熟悉HTML和CSS了（如果还不熟悉的话搞紧去自己复习一下）**  
**在本次项目中，我们会学到 JavaScript 的基础，并掌握 React 的核心知识**  
**最后，我们会用学到的知识做一个小项目，或加入Triple C的前端项目组**  
<br>
**我们每周可能会有一些小作业，但是目前我还没写好orz**  
**写好了之后会更新在这个文档里** 

## 目录：
- [时间安排](#项目时间安排)
- [作业](#作业)
- [Homwork instructions](#Homwork_instructions)

## 项目时间安排：
### week 1 - JavaScript：
**学习 [Educative.io - JavaScript Fundamentals Before Learning React](https://www.educative.io/courses/javascript-fundamentals-before-learning-react)**
- Due 2/28/2021
- 这是本项目里面最后一次使用 Educative.io 这个平台
- 只用学到第四章及以前（Classes)，后面内容选学。不看也没事，我们后面会更详细地学到这些内容
- 总学习时间大概 <= 2 hours
- **作业:**
    - hw1: 完成里面的前三个taskN.js，task4.js选做
    - due 3/7/2021 

**从第二周开始，我们会使用这个 [YouTube 教程](https://www.youtube.com/watch?v=QFaFIcGhPoM&list=PLC3y8-rFHvwgg3vaYJgHGnModB54rxOk3&ab_channel=Codevolution)**
### week 2 - Introduction to React:
- **学习YouTube教程的 1 - 6 节**  
- 前面的内容很简单，建议他讲些有的没的的时候就开 1.5+ 倍速看
- 总学习时长不超过一个小时

### week 3 - Props and State:
- **学习YouTube教程的 7 - 13 节**  
- 总学习时长大概一小时多一点
- 着重理解如何向组件传递参数，以及组件该如何使用（或保存）这些参数

### week 4 - Event handling:
- **学习YouTube教程的 14 - 19 节**  
- 着重理解 JavaScript 的 ```this```
- 可以看看这个文章：[链接](https://www.javascripttutorial.net/javascript-this/)
- 理解 ```.bind(), .apply(), .call()``` 这三个function到底是干什么的
- 理解为什么一定要
    ```javascript
    this.onClick = this.onClick.bind(this);
    ```
    才不会报 ```Cannot perform .setState() of undefined``` 之类的错误  
    想清楚上面这句话到底是什么意思，到底 interpreter 觉得什么东西是```undefined```的  
    想清楚```bind()```是干什么的，会 return 什么东西；每个地方的```this```是干什么的
- 理解为什么用 ```arrow function``` 来替代 ```regular function```，即使不 ```bind()``` 也不会报错
- 考虑到本周的内容比较难，而且涉及到JavaScript中的难点，学习时间大约两小时起步


### week 5 - 没想好取啥名儿:
- **学习YouTube教程的 20 - 25 节**  
- 看完YouTube之后，看一下我之前录的 [Axios, Material UI, 和 React Router 的教程](https://drive.google.com/file/d/1qfohK3fd6cu3AfuOaqx1CtFZw2rXGfYR/view?usp=sharing)
- 总学习时长大约两小时起步，但是内容都不会很难  

## 作业：
 - 所有作业都在 [这个Github Repo](https://github.com/TripleC-Educational/React-WI21-hws)
 - 如何获取及提交作业，请见下方的instructions
 - hw1 已发布: 3/1/2021

## Homwork_instructions: 
### Set up:
1. 进入[这个链接](https://classroom.github.com/a/efxXn9i9) 来接受Github Assignment, 接受之后，Github会自动创建一个空的Github Repository, 地址为 ```https://github.com/TripleC-Educational/react-wi21-submissions-xxxx``` 其中 ```xxxx``` 是你的Github用户名。这个Repository是你提交作业的地方。
2. 在你的电脑上新建一个文件夹，名称随意
3. 进入那个文件夹，然后 执行 ```git init```
4. 
    在你的那个文件夹里
    ```
    git remote add upstream https://github.com/TripleC-Educational/React-WI21-hws
    ```
    你以后会从这个repository获取最新的homework
5. 
    ```
    git remote add origin https://github.com/TripleC-Educational/react-wi21-submissions-xxxx
    ```
    其中 ```xxxx``` 是你的Github用户名

### 获取作业：
- 在你本地的文件夹里
    ```
    git pull upstream master
    ```
    执行这个pull request之后，你会获取到最新的作业  
    比如第一周的作业应该就会在 ```hw1``` 这个文件夹里
- 以后每周有新的作业发布时，在本地执行这个命令就会获取到最新的作业

### 提交作业：
1. 
    ```
    git add .
    ```
2. 
    ```
    git commit -m 'xxxx'
    ```
3. 
    ```
    git push origin master
    ```
    这会把你的作业push到 ```https://github.com/TripleC-Educational/react-wi21-submissions-xxxx``` 这个 repository