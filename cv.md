[![photo-2021-12-22-11-30-33.jpg](https://i.postimg.cc/nrnW7ngV/photo-2021-12-22-11-30-33.jpg)](https://postimg.cc/G8Sznnb6)
<br>
<br>

# Denis Voronin <br>
E-mail:&nbsp; denis.voronin@gmail.com <br>
Phone: +7.123.456.78.90 <br>
GitHub:&nbsp;[caerdroia](https://github.com/caerdroia) <br><br>

-------------------------------------------
## About me <br>

* *My professional priority for 2022 is to reach sufficient proficiency in JavaScript so that I could feel myself rather comfortable using it on commercial projects.* 
* *Strong points: love challenges, love to solve problems, love to learn.*
* *I started learning Java in October 2021 as I wanted to become a Salesforce Developer and it's tech stack includes APEX which is JAVA-like. Now I'm learning JavaScript as it is also part of the Salesforce stack. Even the bigger one.* <br>

## Programming Skills<br>
* *Java Core*;<br>
* *OOP principles (SOLID)*;
* *Basic Data Structures & Algorithms*;
* *Basic HTML & CSS*;<br><br>

## Code Example<br>

<code>import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        minDivisor(0);
    }
    static void minDivisor(long number) {

        while (true) {

            Scanner scanner = new Scanner(System.in);
            System.out.print("Введите число: ");
            number = scanner.nextInt();

            if (number < 1) {

                System.out.println("Число должно быть больше нуля");
            }

            for (int i = 2; i <= number; i++) {

                if (number < 4 || i == number) {
                    System.out.println("Число простое");
                    break;
                }
                else if (number % i == 0 && i != number) {
                System.out.println(i);
                break;
                }
            }
        }
    }
}
</code>



