---
layout: default
---

# Koshort
한국어 NLP 라이브러리 프로젝트 Koshort(코숏, 한국 길고양이를 부르는 애칭일지도..)을 소개합니다!
Koshort은 현재 총 3가지 파이썬 패키지로 이루어져있으며, 다음과 같은 특징을 공통으로 가집니다.

* Windows, Linux, Mac에서 모두 사용이 가능하도록 노력합니다. (호환성 문제에 관해서는 github issue나 pull request로 알려주세요!)
* 손쉬운 설치 (코드 1줄 내지 2줄)
* Python3를 권장합니다. (pyeunjeon, goorm은 python2에서도 잘 동작합니다!)
* 쉽고 배우기 쉬운 고수준(High-level) API를 제공합니다.

## [Koshort (코숏): 파이썬 한국어 온라인 트렌드 스트리밍](http://koshort.readthedocs.io/ko/latest/)

`pip install koshort`

네이버 실시간 검색어, 트위터 실시간 트윗에 대한 비동기 스트리밍 API와 데이터 파이프라인을 제공하는 패키지.

## [Pyeunjeon (파이은전): 은전한닢 프로젝트와 mecab 기반의 한국어 형태소 분석기의 독립형 python 인터페이스](https://github.com/koshort/peunjeon)

`pip install eunjeon`

한국어 형태소 분석 프로젝트인 은전한닢 프로젝트의 독립형 python 인터페이스.  API는 KoNLPy 스타일을 따르며 이제 누구나 어느 OS(Windows, Mac, Linux)에서나 손쉽게 형태소 분석을 시작할 수 있습니다.

## [Goorm (구름): 한국어를 위한 wordcloud wrapper](https://github.com/koshort/goorm)

`pip install goorm`

파이썬으로 손쉽게 wordcloud를 그려주는 패키지. wordcloud를 이용하여 이제 누구나 한국어 단어만으로도 wordcloud를 만들 수 있습니다. (2017년에 작업했었으나 당시에는 못 써먹을 물건이었기에 업데이트)

## 철학

Koshort은 한국어 NLP 프로젝트인 [KoNLPy](http://konlpy.org)와 [은전한잎](http://eunjeon.blogspot.kr/)에서 영감을 받아 탄생한 프로젝트입니다. 그렇기에 철학도 비슷합니다. 이 프로젝트는 이미 있는 똑같은 NLP 구성요소를 다시 만들기 위한 것이 아니라 기존의 노력들을 모아 누구나 자신들의 프로젝트를 가속화할 수 있도록 돕는 것을 지향합니다.
