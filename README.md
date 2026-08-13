# Laboratory-Activity2_-Gallardo

public class Book {

    // Instance variables
    private String bookID;
    private String title;
    private String author;
    private double price;

    // Parameterized constructor
    public Book(String bookID, String title, String author, double price) {
        this.bookID = bookID;
        this.title = title;
        this.author = author;
        this.price = price;
    }

    // Display method
    public void display() {
        System.out.println("Book ID: " + bookID);
        System.out.println("Title: " + title);
        System.out.println("Author: " + author);
        System.out.println("Price: $" + price);
        System.out.println("------------------------");
    }

    // Main method
    public static void main(String[] args) {

        // Real-life books
        Book book1 = new Book(
            "B001",
            "Harry Potter and the Sorcerer's Stone",
            "J.K. Rowling",
            15.99
        );

        Book book2 = new Book(
            "B002",
            "The Hunger Games",
            "Suzanne Collins",
            14.50
        );

        Book book3 = new Book(
            "B003",
            "The Fault in Our Stars",
            "John Green",
            12.99
        );

        // Display each book
        book1.display();
        book2.display();
        book3.display();
    }
}