---
layout: post
category: study
title: JSP Servlet Day-01
description: >
 JSP Servlet
sitemap: false
hide_last_modified: true
#image: /assets/img/project/pic04.jpg
accent_image: 
  #background: url('/assets/img/project/bmwstartupfarage.gif') center/cover
  #overlay: true
---
## JSP Servlet Day-01

### Servlet 특징

- 자바코드로 구현한 후 컴파일 하고 배포
- 코드가 수정되면 다시 컴파일 하고 패포 → 생산성 저하
- HTML 코드를 Servlet 클래스 네에서 문자열로(”) 작성 해야 하한다.
- 복잡잡도에 따라서 웹페이지 구현이 힘들다.

### Java Server Page(JSP)

HTML내에 Java 코드를 작성하고 웹서버에서 웹 페이지를 생성하여 웹브라우저에 돌려줌

자바를 기반으로 한 스크립트 언어

![Untitled](/assets/img/study/JSP%20Servlet%20Day-01%202a5fdbced84144e5a23169d492fb2b8b/Untitled.png)

### JSP vs Servlet

![Untitled](/assets/img/study/JSP%20Servlet%20Day-01%202a5fdbced84144e5a23169d492fb2b8b/Untitled%201.png)

### include 지시자, 액선

![Untitled](/assets/img/study/JSP%20Servlet%20Day-01%202a5fdbced84144e5a23169d492fb2b8b/Untitled%202.png)

---

웹페이지 이동 방식

1. 리다이렉트 방식 
    - 사용자 요청이 2번 이루워짐
    - response.sendRedirect(”url”)
    - **클라이언트 요청에 의해 서버의 DB에 변화가 생기는 작업에 사용된다.**
2. 포워드 방식
    - 사용자 요청이 1번 이루워짐
    - forward() 사용을 위한 RequestDispatcher 인스턴스 생성
    RequestDispatcher dispatcher = request.getRequestDispatcher(“url”);
    dispatcher.forward(request, response);
    2. request.setAttribute(String, String), request.getAttribute(“String)을 통해 추가적인
    값 전달 가능
    - **특정 URL에 대해 외부에 공개 되지 말하야하는 부분을 가리는데 사용하거나 조회를 위해 사용**
        
        
    
    ![Untitled](/assets/img/study/JSP%20Servlet%20Day-01%202a5fdbced84144e5a23169d492fb2b8b/Untitled%203.png)
    
    쿠키와 세션
    
    쿠키 
    
    브라우저가 종료 되도 정보가 유지 됨 
    
    ![Untitled](/assets/img/study/JSP%20Servlet%20Day-01%202a5fdbced84144e5a23169d492fb2b8b/Untitled%204.png)
    
    세션
    
    브라우저가 종료되기전까지 클라이언트의 정보를 유지하게 해주는 기술
    
    사용자 정보 파일을 서버 측에서 관리
    
    ![Untitled](/assets/img/study/JSP%20Servlet%20Day-01%202a5fdbced84144e5a23169d492fb2b8b/Untitled%205.png)

