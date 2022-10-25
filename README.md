<div align="center">
  <h1>쿼츠 스케줄 시스템 (Spring Boot)</h1>
</div>

<div align="center">
  <img alt="Java" src="https://img.shields.io/badge/Java-%23C6F7E9.svg?style=flat-square&logo=java&logoColor=%23424242" />
  <img alt="Spring" src="https://img.shields.io/badge/Spring-%23C6F7E9.svg?style=flat-square&logo=spring&logoColor=%23424242" />
  <img alt="jQuery" src="https://img.shields.io/badge/jQuery-%23C6F7E9.svg?style=flat-square&logo=jquery&logoColor=%23424242" />
  <img alt="Thymeleaf" src="https://img.shields.io/badge/Thymeleaf-%23C6F7E9.svg?style=flat-square&logo=thymeleaf&logoColor=%23424242" />
</div>
<br>

<div align="left">
  <h2>1. 개발 환경</h2>

- <p><b>OS: </b>Windows 11 (64 Bit)</p>
- <p><b>IDE: </b>IntelliJ</p>
- <p><b>BASE: </b>Open JDK 17.0.3 (Zulu), Gradle 7.4.2</p>
- <p><b>DB: </b>Maria Database</p>
</div>
<br>

<div align="left">
  <h2>2. 환경 설정</h2>

- `application.yaml` 파일에서 `schedule.local`, `schedule.remote` 값을 원하는 경로로 지정한다.
- `build.gradle` 파일에서 `task.deployJar` 스크립트의 배포 경로를 위의 경로로 지정한다.
- `Gradle` 작업 중, `other.deployJar` 스크립트를 실행하여 위의 지정된 경로로 각 모듈을 `.jar` 파일로 패키징한다.
- `IntelliJ` 기준, `Project Structure` > `Project Settings` > `Modules` > `module-core.main` > `JARs or Directories` 선택 후, `.jar` 파일을 클래스 패스에 등록한다.
</div>
