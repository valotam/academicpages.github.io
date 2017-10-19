---
title: "Introduction to Computational Structure Mechanics"
excerpt: "구조역학을 시작하기 전, 재료부터 들어가며..."
collection: csm
permalink: /csm/num1
date: 2017-10-11
---

# 구조역학을 시작하기 전, 재료부터 들어가며...
1. 구조물의 해석을 힘의 평형 방정식을 통해 가능한지, 불가능한지 판단해야한다.  
  즉, 정정/부정정 구조물 분류를 해야한다.  
  이를 위해 구조물 판별식을 활용하면,
* truss
  * reaction + element - 2*node = 0 --> 정정 in 2D
  * reaction + element - 3*node = 0 --> 정정 in 3D
* beam
  * reaction + 3*element - 3*node - hinge = 0 --> 정정 in 2D
  * reaction + 6*element - 6*node - hinge = 0 --> 정정 in 3D

위 식을 통해 정정/부정정 구조물을 파악하고 난 뒤,  
정정 구조물이라면, 힘의 평형방정식을 통해서 문제를 해결하고,  
부정정 구조물이라면, 적합조건과 변형률 관계식을 이용해 문제를 해결한다.
