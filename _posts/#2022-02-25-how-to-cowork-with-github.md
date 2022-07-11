---
layout: post
title:  "How to Co-Work with Github"
date:  2021-02-25 10:00:00 +0900
categories: Experience How-to
---

This is to record how to use github.

# Start
- 공동작업할 원래의 repository (=upstream/main)를 fork하여 나의 깃허브 리모트로 가져옴(my/main)
- 이제, main브랜치는 일치한 상태이다.
- 리모트에서 my/main브랜치로부터 checkout하여 새로운 브랜치를 만든다 (my/01_new)
- my 리포지토리를 로컬로 가져온다. (로컬의 브랜치 main, 01_new가 생성됨) (by Clone)
- 현재 총 5개의 브랜치를 모니터링한다: upstream/main, my/main, my/01_new, main, 01_new

# Working
- 개인 작업은 01_new에서 진행햔다.
- 한번 커밋, 푸쉬후 pull request (PR)을 draft로 생성하여 작업상황 공유.
- 01_new를 작업할 때 커밋, 푸쉬를 하면 my/01_new 및 01_new는 앞서나간다.
- 하지만 upstream/main, my/main, main은 동일한 상태.

# After Working
- PR을 통해 01_new 작업물이 upstream/main으로 merge되도록 한다.
- 그럼 upstream/main, my/01_new, 01_new는 일치된다.
- 이제 upstream/main을 my/main에 merge한다. 
- 로컬main은? my/main을 pull하거나 upstream/main을 merge한다

# How to make PR (pull request) in github
- fork한 branch에서 PR 생성 가능
- 한번 PR이 끝나면 branch를 새로 만들어서 수정 시작

# How to make proto 

  