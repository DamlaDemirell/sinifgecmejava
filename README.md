import java.util.Scanner;

public class test {
    public static void main(String[] args) {
        int turkce, kimya, muzik;

        Scanner input= new Scanner(System.in);

        System.out.println("Türkçe notunuz: ");
        turkce = input.nextInt();

        System.out.println("kimya notunuz: ");
        kimya = input.nextInt();

        System.out.println("Müzik notunuz: ");
        muzik = input.nextInt();

        double average = (kimya + turkce + muzik) / 3;
        if (average <=0 && average <=100 ){
            System.out.println("unfortunately");
        }
        else if(average>55 && average<=100){
            System.out.println("congrats!");
        }
        else{
            System.out.println("ortalamaya katılamadınız.");
        }
    }
}
