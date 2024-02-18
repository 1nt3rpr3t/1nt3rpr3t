```Java
01  public class GithubIntroduction {
02      private final String name;
03      private final String school;
04      private final String discord;
05      private final String instagram;
06      private final String email;
07      private final String[] languages;
08      private final String[] learning;
09      private final String[] tools;
10      private final String[] award;
11      
12      public GithubIntroduction() {
13          this.name = "Yunseong Jeong";
14          this.school = "Gyeongbuk Software High School";
15          this.discord = "itsyunseong";
16          this.instagram = "its_yunseong";
17          this.email = "yunseong.me@gmail.com";
18          this.languages = new String[]{ "C", "Python", "Java", "Html", "Css", "Js" };
19          this.learning = new String[]{ "Spring", "Flask", "MySql" };
20          this.tools = new String[]{ "Git", "Intellij", "Eclipse", "vscode" };
21          this.award = new String[]{"경상북도 창업아이디어 경진대회 금상(1위)"};
22      }
23      
24      public void introduceMyself() {
25          System.out.println("Hello, My Github! My name is " + name + " and I'm 17 years old.");
26          System.out.println("I am a student at the " + school);
27          System.out.println("You can reach me at Discord: " + discord + ", Instagram: " + instagram + ", Email: " + email);
28          System.out.println("I can use these languages: " + String.join(", ", languages));
29          System.out.println("Currently, I'm learning these: " + String.join(", ", learning));
30          System.out.println("These are the tools I use: " + String.join(", ", tools));
31          System.out.println("Here's one of my achievements: " + award);
32      }
33      
34      public static void main(String[] args) {
35          GithubIntroduction yunseong = new GithubIntroduction();
36          yunseong.introduceMyself();
37      }
38  }

```  

### SNS Link
#### 👇👇 Click!! 👇👇
<div>
  <a href="https://www.instagram.com/its_yunseong" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=Instagram&logoColor=white" target="_blank"/></a>
  <a href="https://discord.com/users/839504073304440862" target="_blank"><img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=Discord&logoColor=white" target="_blank"/></a>
  <a href="https://yunseong-kr.notion.site/e0a6f6fd4e364dfcb87d69c8045b9d37?pvs=4" target="_blank"><img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white" target="_blank"/></a>
</div>

<hr>

<div>
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=jyerd333">
</div>

