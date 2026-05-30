# \## Java 다형성 정리

# 

# 호출 가능 여부는 변수 타입 기준이다.

# 

# 실제 실행되는 오버라이딩 메서드는 객체 타입 기준이다.

# 

# 예시:

# 

# ```java

# RoleAction role = new Admin();

# role.performRole();

# 

# role은 RoleAction 타입 변수이고, 실제 객체는 Admin이다.

# 

# 따라서 RoleAction에 선언된 메서드만 호출 가능하지만, 실행되는 메서드는 Admin의 performRole()이다.

# 

# 

# 저장 후 메모장 닫기.

# 

# \---

# 

# \## 3. 수정됐는지 확인

# 

# ```bash

# git status

