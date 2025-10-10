---
title: "02. Meaningful Names"
book: "Clean Code"
authors: ["Robert C. Martin"]
edition: "2008"
chapter: 2
created: 2025-10-11
modified: 2025-10-11
version: 1
tags: ["oop","clean-code","naming","readability"]
related:
  - "../../tags/oop.md"
  - "../../tags/clean-code.md"
---

## 0. TL;DR (3문장 요약)
- 이름은 **의도 드러내기**가 최우선.
- **구체성/도메인 용어**를 사용하고, 불필요한 접두/약어는 지양.
- **같은 개념에는 같은 단어**를 일관되게 쓴다.

## 1. 개념(정의·핵심 문장)
- *“의도가 명확한 이름은 추가 설명 없이도 설계를 전달한다”(p.18)*  
- 변수/함수/클래스 이름은 **역할과 제약**을 반영해야 한다.

## 2. 근거·출처
- p.18~27, 31 (의도 드러내기, 도메인 용어 일관성, 불필요한 정보 제거)

## 3. 실무 적용 (Spring Boot 관점)
### 3.1 컨트롤러/서비스 네이밍
```java
// Bad
public class UserMgr { ... }

// Good
public class UserService { ... }

// 더 구체적으로
public interface PasswordEncoder { ... }
public class BcryptPasswordEncoder implements PasswordEncoder { ... }

