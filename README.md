## Hi there 👋  Welcome! 🇧🇷

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ramoncunha/)](https://www.linkedin.com/in/ramoncunha/)

```java
public class MyProfile {

  public record Developer (
    String name,
    String role,
    String country,
    String currentJob,
    List<String> hobbies,
    String goal
  ) {}

  public static void main(String[] args) {
    final var ramon = new Developer(
      "Ramon",
      "Backend Developer",
      "Brazil",
      "Senior Software Engineer",
      List.of("Car detailing", "FPS Player"),
      "Tech Lead"
    );

    while(true) {
      code(ramon);
    }
  }

  public static void code(Developer dev) {
    System.out.printf("%s is coding..", dev.name());
  }
}
```

### ✨ I'm Ramon! ✨

- 💼 Working as Software Engineer, specialize in Back-end Development at Inter&Co.
- 🚀 My stack is Java, Micronaut, Spring Boot, PostgreSQL, AWS, Kafka and Kubernetes.
- 📫 Reach me out at LinkedIn and checkout my blog [here](https://ramoncunha.netlify.app/).
- 🌱 I’m currently learning Node.js and Go.
