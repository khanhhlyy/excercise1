package exercise1;

import java.util.Date;

public abstract class Book implements Idbook {

    String bookId;
    private String publisher;
    private Date entryDate;
    private double unitPrice;
    private double quantity;

    public Book(String booId, String publisher, Date entryDate, double unitPrice, double quantity) {
        this.bookId = bookId;
        this.publisher = publisher;
        this.entryDate = entryDate;
        this.unitPrice = unitPrice;
        this.quantity = quantity;
    }

    @Override
    public void addBook() {
        System.out.println("Add Book: ");
    }

    public void updateBook(String id) {
        if (this.bookId.equals(id)) {
            System.out.println("Update book id: " + id);
        } else {
            System.out.println("Update book not found");
        }
    }

    public void displayBook() {
        System.out.println("Book id: " + bookId);
        System.out.println("publisher: " + publisher);
        System.out.println("entryDate: " + entryDate);
        System.out.println("unitPrice: " + unitPrice);
        System.out.println("quantity: " + quantity);

    }
}
