# Remove-spaces-from-a-string-entered-from-the-keyboard
Remove spaces from a string entered from the keyboard
import java.util.Scanner;
public class Main {
  public static void main(String[] args) {
    //sử dụng class Scanner để lấy dữ liệu từ bàn phím.
    Scanner sc = new Scanner(System.in);
    System.out.print("\n\nNhập vào chuỗi cần kiểm tra: ");
    String input = sc.nextLine();
    //hiển thị chuỗi ban đầu
    System.out.println("Chuỗi ban đầu: " + input);
 
    //sử dụng phương thức replaceAll() để thay thế " " bằng "".
    input = input.replaceAll("\\s", "");
    System.out.println("Chuỗi sau khi xóa khoảng trắng: " + input);
 
    System.out.println("\n----------------------------------");
    System.out.println("Chương trình này được đăng tại Freetuts.net");
  }
}
