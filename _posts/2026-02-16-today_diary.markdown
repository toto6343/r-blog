---
layout: post
title: "R Markdown 실습 : 수치화 및 그래프 시각화"
author: "Test"
date: 2026-02-16
categories: [R, DataAnalysis, Practice]
---

## 📌 실습 목적

본 글은 **R Markdown을 활용한 데이터 분석 결과를  
Jekyll 블로그에서 마크다운(md) 형태로 표현하는 실습**이다.

R Markdown에서 계산한 **수치 요약 결과**와  
**그래프 시각화 결과**를 md 문서로 정리하여 게시한다.

---

## 📊 데이터 설명

- 사용 데이터셋: `cars`
- 변수 설명
  - `speed`: 자동차 속도
  - `dist`: 제동거리

---

## 📈 수치 요약 결과

`summary(cars)` 실행 결과를 바탕으로 주요 통계를 정리하였다.

### speed (속도)

- 최소값: 4  
- 중앙값: 15  
- 평균값: 15.4  
- 최대값: 25  

### dist (제동거리)

- 최소값: 2  
- 중앙값: 36  
- 평균값: 42.98  
- 최대값: 120  

```text
speed:
 Min.   : 4.0  
 Median : 15.0  
 Mean   : 15.4  
 Max.   : 25.0  

dist:
 Min.   :  2  
 Median : 36  
 Mean   : 42.98  
 Max.   : 120  

## Including Plots

You can also embed plots, for example:

![Pressure Plot](/assets/img/pressure.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.