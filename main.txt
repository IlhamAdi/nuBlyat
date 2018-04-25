import java.util.Scanner;
public class Main {
public static void main(String[] args) {
int data;
Scanner sc = new Scanner(System.in);
System.out.print("Masukkan angka (10-100) : ");
data = sc.nextInt();
if (data > 60)
System.out.println("Baik");
else if (data > 40)
System.out.println("Kurang");
else
System.out.println("Sangat Kurang");
}
}
