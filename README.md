//paper , scissor , rock game using java
//includes java scanner class , switch case and if-else conditions.
import java.util.* ;
public class Q17 {
    public static void main(String[] args) {
     Random num = new Random();
     Scanner s = new Scanner(System.in);
     int num1 = num.nextInt(3);
        System.out.println("paper , scissors , rock game starting : ");
        System.out.println("the choices are : ");
        System.out.println("1 : paper\t 2 : scisscor\t 3 : rock");
        System.out.println("make your choice : ");
        int choice = s.nextInt();
        System.out.println("computer has chosen : " + num1);
        switch (choice)
        {
            case 1 :
                if (num1 == 1)
                {
                    System.out.println("game is draw.");
                }
                else if (num1 == 2)
                {
                    System.out.println("you loss.");
                }
                else if (num1 == 3)
                {
                    System.out.println("you win.");
                }
                break ;
            case 2 :
                if (num1 == 1)
                {
                    System.out.println("you win.");
                }
                else if (num1 == 2)
                {
                    System.out.println("game is draw.");
                }
                else if (num1 == 3)
                {
                    System.out.println("you loss.");
                }
                break ;
            case 3 :
                if (num1 == 1)
                {
                    System.out.println("you loss.");
                }
                else if (num1 == 2)
                {
                    System.out.println("you win.");
                }
                else if (num1 == 3)
                {
                    System.out.println("game is draw.");
                }
                break ;
        }
    }
}
