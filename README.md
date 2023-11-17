import java.util.Scanner;

class LibrarySys {
    public static void main(String[] args) {
        Scanner myObj = new Scanner(System.in);
        System.out.println("Enter book name, author, serial, year published:");

        String bookname = myObj.nextLine();
        String author = myObj.nextLine();
        int serial = myObj.nextInt();
        int yearpublished = myObj.nextInt();

        System.out.println("Book name: " + bookname);
        System.out.println("Author: " + author);
        System.out.println("Serial: " + serial);
        System.out.println("Year published: " + yearpublished);
    }
}
