**Use case : 자전거 정보 등록**

| Actor Action                     | System Respone         |
| -------------------------------- | ---------------------- |
| 1. 관리자가 (자전거 ID, 자전거 제품명)를 입력한다. | 2. 자전거 정보가 등록되었음을 알린다. |

**Use case : 자전거 대여**

| Actor Action                               | System Respone        |
| ------------------------------------------ | --------------------- |
| 1. 회원이 대여할 자전거의 정보(자전거 ID, 자전거 제품명)을 입력한다. | 2.  자전거가 대여 되었음을 알린다. |

**Use case : 대여중인 자전거 정보 조회**

| Actor Action | System Respone                                 |
| ------------ | ---------------------------------------------- |
| 1. None      | 2. 해당 리스트가 출력되고, 각 항목에는 자전거 ID, 자전거 제품명을 보여준다. |

**Use case : 회원 가입**

| Actor Action                    | System Respone        |
| ------------------------------- | --------------------- |
| 1. 필수 정보(ID, 비밀번호, 전화번호)를 입력한다. | 2. 회원가입 완료 메세지가 표시된다. |

**Use case : 로그인하기**

| Actor Action        | System Respone       |
| ------------------- | -------------------- |
| 1. 아이디와 비밀번호를 입력한다. | 2. 로그인 성공 메세지가 출력된다. |

**Use case : 로그아웃하기**

| Actor Action | System Respone        |
| ------------ | --------------------- |
| 1. None      | 2. 로그아웃 메세지 화면이 출력된다. |
