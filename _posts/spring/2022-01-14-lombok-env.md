---
layout: post
title: lombok 설치
subtitle: lombok install
categories: spring, env
tags: [spring, env]
---

# LOMBOK 설치하는 방법

1. jar 파일 다운로드

[https://projectlombok.org/download](https://projectlombok.org/download)

![a1.png](/assets/images/env/lombok/a1.png)

2. Window + r

cmd 명령프롬프터 켜기

cd [jar 파일이 있는 파일디렉토리]

java -jar lombok.jar 입력

![a2.png](/assets/images/env/lombok/a2.png)

3. 완료된 화면

![a3.png](/assets/images/env/lombok/a3.png)

4. dependency 등록

<dependency>

<groupId>org.projectlombok</groupId>

<artifactId>lombok</artifactId>

<version>1.18.16</version> <!--버전은 그때 맞춰서 20201018기준-->

</dependency>

### 자주 사용하는 lombok annotation

@NoArgsConstructor  //파라미터가 없는 생성자

@AllArgsConstructor // 파라미터가 있는 생성자

@Getter @Setter  // getter setter

@ToString  // tostring

@RequiredArgsConstructor // 파라미터 일부가 잇는 생성자

// final 이나 @NonNull인 필드 값만 파라미터로 받는다

![d1.png](/assets/images/env/lombok/d1.png)

@exclude

특정 필드를 toString결과에서 제외시킬 수 있습니다

![d2.png](/assets/images/env/lombok/d2.png)

@Data

// 위에서 설명한 @Getter @Setter @RequiredArgsConstructor @ToString @EqualAndHashCOde 를 한꺼번에 설정해주는 매우 유용한 어노테이션

![d3.png](/assets/images/env/lombok//d3.png)
