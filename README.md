# **Open-source Software**

#### Introduction
 * 담당학과
   * Artificial Intelligence(인공지능학부)  
 * 수강학년
   * 2nd Year
 * 담당교수 
   * Kwanghoon Choi
 
-------------
### Week1-1 강의 개요 (강의계획서)
* 수업목표 
  * Basic functional programming, **_Haskell_** (기초 함수형 프로그래밍 하스켈)
  * Basic concepts and tools for **_open-source software_** development (오픈소스 소프트웨어 기본 개념과 도구)
  * **_Attitude to self-learn_** new SW tools and environments (새로운/낯선 소프트웨어 개발 환경 및 도구를 스스로 배우는 태도)

* 강의진행방식
  * 오픈소스SW활용 **_Git, Visual Studio Code, Haskell tools, Haskell-mooc_**

* 주차별 수업계획
  1. Introduction
  2. Command-based environments (**_커맨드 기반 환경_**)
  3. Git (**_Git_**)
  4. Haskell MOOC Lecture 1 - Overview (**_하스켈 무크 1강 - 개요_**)
  5. Haskell MOOC Lecture 1 - Basic (**_하스켈 무크 1강 - 기초_**)
  6. Exercises(연습문제)
  7. **_중간고사_**
  8. Haskell MOOC Lecture 2 (**_하스켈 무크 2강_**)
  9. Exercises(연습문제)
  10. Haskell MOOC Lecture 3 (**_하스켈 무크 3강_**)
  11. Exercises
  12. Haskell MOOC Lecture 4 (**_하스켈 무크 4강_**)
  13. Exercises(연습문제)
  14. **_TBD_**
  15. **_기말고사_**

-------------
### Week1-2 Introduction to Open Source Software
* What is Open Source Software?
  > oftware whose copyright holder gives the right to publish, use, copy, modify, and distribute the source code to everyone.  
  > 소프트웨어 저작권 소유자가 모든 사람에게 소스 코드를 **게시, 사용, 복사, 수정 및 배포할 권리를 부여한 소프트웨어**
* OSS License
  > The scope of use, reproduction, modification, and distribution rights of the open source software  
  > OSS라이선스 : **오픈소스 소프트웨어의 사용, 복제, 수정, 배포 권한의 범위를 지정**
#### Commercialization View (**_상용화 관점_**)  
* **Commercial SW** (E.g. Windows)
  * Individual License (EULA) (**개별 이용허락**)  
  * Royalty (**로열티 지급**)
  * Binary only (**실행 바이너리만 제공**)
  * No reproduction, distribution, and modification (**복제, 배포, 수정 불가**)
  * Limited terms and purposes (**사용 기간과 목적 제한**)
  
* **Open Source SW**
  * Open Source Lincense (**일괄 사전 이용허락**)
  * No Royalty (**로열티 없음**)
  * Source code (**소스 코드 제공**)
  * Reproduction, distribution, and modification are permitted (**복제, 배포, 수정 허용**)
  * No limitation on terms and purposes (**기간/목적 제한 없음**)
  
#### Philosophical View (**_OSS에 대한 철학적 관점_**)  
> **Free Software**   vs.  **Open Source Software**   

* Free Software (자유 소프트웨어)  
**Richard Stallman** – Creator of GNU Project  
![Richard Stallman](https://www.computerworld.es/archivos/201909/asco.png)  
FSF (Free Software Foundation, 1984~)  
GPL 1.0 (1989), GPL 2.0 (1991), GPL 3.0 (2007)  
Copyleft  (No SW patent, No DRM)

* Open Source Software  
**Eric S. Raymond** – Author of The Cathedral and the Bazzar   
![Eric Steven Raymond](https://image.slidesharecdn.com/ufpel-sl-120528095126-phpapp01/95/tudo-que-voc-sempre-quis-saber-sobre-software-livre-mas-no-tinha-coragem-de-perguntar-53-728.jpg?cb=1338198942)  
OSI (Open Source Initiative, 1998~)  
Ambiguity of free  
Combination of OSS and Closed Source SW  
License under law

-------------
### Week2-1 Introduction to Version Control System  
* Version Control System (**_VCS_**)
  * Track your files over time so that you can easily get back to a previous working version
  * **VCS software**
    * CVS (Concurrent Version System)
    * SVN (Subversion)
    * Mercurial
    * Darcs
    * Git
  * Repository or Repo (**저장소**)
 
* Two Main Types of **VCS**
  * **_Centralized_** VCS
    * One central repository with many users
    * E.g., CVS, SVN, Darcs  
![Centralized VCS](https://betterexplained.com/wp-content/uploads/version_control/distributed/centralized_example.png)

  * **_Decentralized (Distributed)_** VCS
    * Every user owns his or her local repository
    * A separate remote (central) repository
    * Sometimes, more than one remote (central) repositories

    * Two new actions (with remote repositories): fork pull request

    *  E.	g., GIT, Mercurial  
 ![A distributed version control system](https://betterexplained.com/wp-content/uploads/version_control/distributed/distributed_example.png)


-------------
### Week2-2 An Introduction to GIT
* Linus Torvalds
  * For collaboration of development of Linux kernel

* A distributed version control system
  * Workspace : files you are working with
  * Index: (staged) files to be considered in the next commit
  * Local repository : files committed to the local repo
  * Remote repository : files pushed to the remote repo  

![Git: workflow](https://lh5.googleusercontent.com/23bMnH5q8_E9rSf4zRDE67KJtUEgRZA9ORKfZyqo-jPU-oxIDKcua1XekpAJ9p2U3W9vH1Bg69ipBPyOUDYSdJcKiTfgDtt6KBCguHf2DdPZGzccM1XgUW9YDzySwH6jumNUIgeq7yjf4VgDR6Th_w4kiww4WzOHCS75om5STTl-GeA3bwSy4cAORd4pHNg)


-------------
### Week2-3 Github, fork, pull request
##### **Training Environment**
  > 1. Download Git
  >     * [Git](https://git-scm.com/downloads)   
  > 2. Download Editor
  >     * [Editor](https://atom.io/)
  > 3. Github Sign up
  >     * [Github](https://github.com/join)

##### **Join here, and do it !**
  > [tutorial](https://github.com/Taeung/git-training)

-------------
### Week3   Introduction to Markdown
* A lightweight markup language for creating formatted text using a plain-text editor  
    * John Gruber and Aaron Swartz (2004)
    * Widely used in readme files in Github
* References
    * Wiki [Link](https://en.wikipedia.org/wiki/Markdown)
    * Markdown tutorial [Link](https://www.markdowntutorial.com)
    * Github tutorial [Link](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
    * GitHub Flavored markdown spec [Link](https://github.github.com/gfm/)
    
#### Examples
#### **Headings**
>   * Headers are frequently used on websites, magazine articles, and notices, to draw attention to a section.  
>       헤더는 웹사이트, 잡지 기사, 공지사항에 자주 사용되어 한 구획에 대한 이목을 끌도록 합니다.
>   * To make headers in Markdown, you preface the phrase with a hash mark (#)  
>       마크다운에서 헤더를 만들기 위해, 해쉬 마크(#)를 문단 앞에 사용하면 됩니다.
>   * You place the same number of hash marks as the size of the header you want  
>       원하는 헤더 사이즈 크기만큼 해쉬 마크 갯수를 늘려 사용하면 됩니다. (1 ~ 6size)
  
#### **Italic, bold**
>   * To make a phrase italic in Markdown, you can surround words with an underscore (_ ).  
>       마크다운으로 이탤릭체 를 사용하기 위해서 글자의 바깥쪽에 밑줄(_)을 추가하면 됩니다.  
>   * to make phrases bold in Markdown, you can surround words with two asterisks ( ** ).  
>       마크다운에서 볼드체를 사용하기 위해서, 글자의 바깥쪽에 별표( ** )를 추가하면 됩니다.

#### **Links**
>   *  There are two different link types in Markdown, but both of them render the exact same way  
>       마크다운에는 두 가지 링크 유형이 있지만, 두 링크 유형 모두 정확히 같은 방식으로 렌더링됩니다.
>   *  The first link style is called an inline link. To create an inline link, you wrap the link text in brackets ( [ ] ), and then you wrap the link in parenthesis ( ( ) ).  
>       첫 번째 링크 스타일은 인라인 링크라고 불립니다. 인라인 링크를 만들기 위해선, 여러분은 링크할 텍스트를 대괄호( [ ] )로 싼 다음, 링크할 주소를 소괄호로( ( ) )로 감싸면 됩니다.
>   *  The other link type is called a reference link. As the name implies, the link is actually a reference to another place in the document.  
>       다른 링크 타입은 참조 링크 입니다. 이름에서 알 수 있듯이, 참조 링크는 실제로 문서 내의 다른 위치에 대한 참조를 나타냅니다
>   *   An advantage of the reference link style is that multiple links to the same place only need to be updated once.  
>       참조 링크 스타일의 장점은 같은 장소에 대한 다중 링크는 한 번만 업데이트하면 된다는 것입니다
>   *  You define them by providing the same tag name wrapped in brackets, followed by a colon, followed by the link.  
>       참조 링크를 정의하는 방법은 대괄호로 묶은 참조 태그를 작성하고 그 다음에 콜론, 그 다음에 링크할 주소를 작성하면 됩니다.

#### **Images**
> * Images also have two styles, just like links, and both of them render the exact same way.  
>   여러분이 마크다운에서 링크를 사용할 줄 안다면, 이미지도 사용할 수 있습니다. 두 문법이 거의 동일합니다.
> * The first image style is called an inline image link. To create an inline image link, enter an exclamation point ( ! ), wrap the alt text in brackets ( [ ] ), and then wrap the link in parenthesis ( ( ) ).  
> 첫번째 이미지 타입은 인라인 이미지 링크라 부릅니다. 인라인 이미지 링크를 사용하기 위해 느낌표를 입력하고 ( ! ), 대괄호로 ( [ ] ) 대체 텍스트(Alt Text)를 감싼 다음, 소괄호로 ( ( ) ) 링크를 감싸면 됩니다.


#### **Blockquotes**
> * To create a block quote, all you have to do is preface a line with the "greater than" caret (>).  
>     인용문을 사용하기 위해서, 여러분이 해야할 것은 문장 앞에 "~보다 큰" 의미를 가진 캐럿 기호 (>)만 붙여주면 됩니다.

#### **Lists**
> * There are two types of lists in the known universe: unordered and ordered.  
>   리스트 타입은 보통 2가지가 존재합니다. 순서가 매겨지지 않은 것(unordered)과 순서가 매겨진 것(ordered)입니다. 
> * To create an unordered list, you'll want to preface each item in the list with an asterisk ( * ).
>   순서가 매겨지지 않은 리스트를 생성하기 위해 여러분은 리스트의 각 항목에 별표( * )를 앞에 붙여주면 됩니다
> * An ordered list is prefaced with numbers, instead of asterisks  
>   순서가 매겨진 리스트는 별표(*)대신에 숫자를 붙이면 됩니다. 
