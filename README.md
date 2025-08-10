Repository

Repository는 데이터 접근을 담당하는 계층이다.

여기서 말하는 데이터 접근은 RoomDatabase나 Retrofit을 통해 데이터를 가져오는 작업을 말한다.

Repository는 데이터를 가져오고, ViewModel은 Repository에 데이터를 요청하고 사용한다.

(코드가 간결해지고, 테스트 용이성이 향상 된다)
