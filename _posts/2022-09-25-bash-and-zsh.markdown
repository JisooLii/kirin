---
layout: post
title: Bash와 Zsh의 차이
date: 2022-09-15 15:23:00 +0900
description: Bash와 Zsh 의 차이를 알아보자
published: false
img: post/2022-09-15/starting-1.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: ["bash", "zsh"]
---

# 쉘

쉘 (Shell) 이란 운영 체제에서 운영 체제 기능과 서비스를 사용자가 이용할 수 있도록 인터페이스를 제공해주는 애플리케이션을 말합니다.<br>
운영체제 내부인 커널과 사용자 간의 인터페이스를 감싸고 있는 층이기 때문에 "껍데기"라는 뜻을 가진 "shell"이라는 이름이 붙었다고 합니다.<br>
유저는 커맨드를 통해 쉘에게 명령을 내리고, 쉘은 이를 처리할 수 있습니다.

쉘도 여러가지 종류가 있는데, 이 중에서 가장 유명한 두 가지인 Bash와 ZSH에 대해서 간략하게 알아봅시다.

# Bash

Bash는 Bourn-Again Shell의 약자입니다. 초기 UNIX 쉘 중 하나였던 본 쉘로부터 파생된 것이구요.<br>
대부분 유명한 리눅스 배포판에서는 이 Bash를 기본 쉘로 사용합니다.<br>
대표적으로 Ubuntu, Linux Mint, Solaris 11, Pop OS 등이 Bash를 기본 쉘로 사용하고 있구요.<br>
윈도우에서도 사용 가능합니다.

Bash는 .bashrc 파일을 non-login interactive shell에서,
.bash_profile을 login shell에서 읽어 설정을 적용합니다.

# Zsh (Z shell)

Zsh 또한 Bash와 마찬가지로 커맨드라인 인터프리터와 로그인 쉘로써 모두 사용 가능한 쉘입니다.<br>
bash를 기반으로 작성된 쉘이긴 한데, 몇 가지 추가 기능을 제공합니다.<br>
Mac OS와 Kali Linux에서 기본 쉘로 설정되어 있구요,<br>
플러그인 지원이나 커스텀 기능, 테마 지원 및 스펠링 체크 기능 등을 제공하고 있어서 기능적으로 더 유연하다고 볼 수 있습니다.

Zsh는 .zshrc를 interactive shell에서, .zprofile을 로그인 쉘에서 읽어 설정을 적용합니다.

출처: Geeks For Geeks (사이트[site])

[site]: https://www.geeksforgeeks.org/bash-scripting-difference-between-zsh-and-bash/
